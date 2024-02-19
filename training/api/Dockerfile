# Use the official TensorFlow Serving runtime as a parent image
FROM tensorflow/serving

# Set the working directory in the container
WORKDIR /models

# Copy the FastAPI application code into the container
COPY tf-serving.py .

# Set environment variables
ENV MODEL_NAME painters_model
ENV MODEL_PATH D:\Code\impressionists\models\1

# Expose the port that TensorFlow Serving will use
EXPOSE 8501

# Command to run TensorFlow Serving
CMD ["tensorflow_model_server", "--port=8501", "--rest_api_port=8502", "--model_name=${MODEL_NAME}", "--model_base_path=${MODEL_PATH}/${MODEL_NAME}"]
