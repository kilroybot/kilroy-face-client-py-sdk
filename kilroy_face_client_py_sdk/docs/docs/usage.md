# Usage

You can this package to interact with faces.

The easiest way is to use the `FaceService` class.
It provides a high-level interface to all the methods of the service.
All methods are either coroutines or async iterators.

Here's an example:

```python
from kilroy_face_client_py_sdk import FaceService

service = FaceService(host="localhost", port=10000)

await service.get_metadata()
```
