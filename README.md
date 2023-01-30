### To start download dependencies
pip install requirements.txt

### To start the model first go to the working directory and run
python -m uvicorn model_test_1:app --reload

### To integrate with the model go to
<a href='http://127.0.0.1:8000/docs'> http://127.0.0.1:8000/docs </a>


##### In the POST section upload your video to get the frames with different angles

<em> You can change the original code source and API would be reloaded automatically </em>

pose_identify.py is for the live camera face recognition and frames extraction. FYI change the directories first.
