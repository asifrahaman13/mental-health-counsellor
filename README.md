# MENTAL HEALTH BOT 👨🏼‍⚕️

## How to run the code

First clone the repository: 

```
git clone https://github.com/asifrahaman13/mental-health-counsellor
```

Next enter into the backend directory.

```
cd backend/
```

Create a virtual environment. 

```
virtualenv venv
```

Activate the virtual environment. In unix based system like the Linux or Mac OS you can follow the following commands: 

```
source venv/bin/activate
```

Now install the required dependencies.

```
pip install -r requirements.txt
```

Next enter the data into the .env file.

Now run the backend server.

```
uvicorn main:app --reload
```


Next you need to open another terminal to run the front end application. 

```
cd frontend/
```

Now install the required dependencies. 

```
yarn install 
```

Now start the development server in the front-end using the following command:

```
yarn start
```


<br/>
<br/>
<br/>

**MIT License**

## Copyright (c) 2023 Asif Rahaman

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.