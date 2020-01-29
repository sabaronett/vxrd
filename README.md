# vxrd
### Interactive X-Ray Diffraction Calculator

This repository is intended for basic Flask understanding and preliminary developement. The main repository can be found at https://github.com/qzhu2017/XRD.

In order to run this web-app locally, run the following shell commands:
```bash
$ cd XRD
$ pip install -r requirements.txt
$ flask run
```
It's **important** to rerun `pip install -r requirements.txt` if this repository has been updated in case there are new dependencies.

If everything is setup correctly, you should see the following output:
```bash
 * Serving Flask app "microblog.py"
 * Environment: production
   WARNING: This is a development server. Do not use it in a production deployment.
   Use a production WSGI server instead.
 * Debug mode: off
 * Running on http://127.0.0.1:5000/ (Press CTRL+C to quit)
```
Then, open your web browser and enter the following URL:
`http://localhost:5000/`

When finished, press `CTRL+C` in your terminal to shutdown the web-app.
