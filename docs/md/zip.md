# `MFZipFile`

Python's `ZipFile` doesn't preserve execute permissions. The `MFZipFile` subclass modifies `ZipFile.extract()` to do so, as per the recommendation [here](https://stackoverflow.com/questions/39296101/python-zipfile-removes-execute-permissions-from-binaries).