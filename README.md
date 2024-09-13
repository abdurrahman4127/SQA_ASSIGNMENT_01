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
Now if it's all done, then instal **Flask** with the following command:
```bash
pip install Flask
```

At this moment, the setup stages are all done, what reamins is that the python application/api that is to be run. Now, the assignment file (app.py) is added to this directory, and the **Flask** app needs to be exported to the environment. To do that, do this:
```bash
export FLASK_APP=app.py
export FLASK_ENV=development
```

All good? Then run the **Flask** by:
```bash
flask run
```

If you ain't as dumb as me, then you should be able to see the app at `http://127.0.0.1:5000`, or maybe try **postman** as sir wanted you to.

## Assignment Starts:
### 1. API1: Student/
