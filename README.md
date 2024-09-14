# SQA_ASSIGNMENT_01

### Setup
Ight, first make sure that the system (why not Linux, huh?) has **python3** installed, if it ain't installed already, then run the following command:
```bash
sudo apt install python3 python3-pip
```

After that, setup a virtual environment (venv), and source it (i.e. activate it) by:
```bash
sudo apt install python3-venv
python3 -m venv venv
source venv/bin/activate
```
Now if it's all done, then install **Flask** with the following command:
```bash
pip install Flask
```

At this moment, the setup stages are all done, what remains is that the python application/API is to be run. The assignment file (app.py) is added to this directory, and the **Flask** app needs to be exported to the environment. To do that, do this:
```bash
export FLASK_APP=app.py
export FLASK_ENV=development
```

All good? Then run the **Flask** by:
```bash
flask run
```

If you ain't as dumb as me, then you should be able to see the app at `http://127.0.0.1:5000`, or maybe try **postman** as sir wanted you to.

### Document
The detailed implementation of the test cases is at [Assignment](https://github.com/abdurrahman4127/SQA_ASSIGNMENT_01/blob/main/SQA_Assignment.docx)

### Postman Collection
Postman collection of experiments is at [PostmanJsonFile](https://github.com/abdurrahman4127/SQA_ASSIGNMENT_01/blob/main/SQA_ASSIGNMENT_01.postman_collection.json)
