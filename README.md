# Dokku Python and Static Buildpack using Nginx

Makes some (silly) assumptions:

* Python code in a `BACKEND` folder
* Static code in a `FRONTEND/webapp` folder

To use, create an `.env` file in your project containing this:

    BUILDPACK_URL="https://github.com/ruudud/python-with-static-buildpack.git"

