## Instructions to build a Container Image 

  * Base Image : `python:3.9-slim`
  * Copy over everything in the build context (streamlit_app) path
  * Installing Dependencies : `pip install -r requirements.txt`
  * Port: 8501 
  * Launch Command : `streamlit run app.py --server.address=0.0.0.0`
  * To create container: docker run -e "API_URL=http://192.168.1.74:8005" -idtp 8051:8051 streamlit_app:v1


  