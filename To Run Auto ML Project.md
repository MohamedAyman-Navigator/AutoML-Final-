# 1. Activate your Anaconda environment
conda activate work

# 2. Set your API key for the current session
export GOOGLE_API_KEY="your_actual_api_key_here"

# 3. Navigate to your project's root directory
cd /media/mohamed-ayman/206EF8B16EF880B8/ml

# 4. Start the web server
uvicorn automl_api.main:app --reload
