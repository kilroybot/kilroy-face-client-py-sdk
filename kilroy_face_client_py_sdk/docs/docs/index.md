# kilroy-face-client-py-sdk

SDK for kilroy face clients in Python 🧰

## Installing

Using `pip`:

```sh
pip install kilroy-face-client-py-sdk
```

## Usage

```python
from kilroy_face_client_py_sdk import FaceService

service = FaceService(host="localhost", port=10000)

await service.get_metadata()
```
