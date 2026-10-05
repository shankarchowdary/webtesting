Unity WebAR ArUco Template

1. Use Unity 6000.3.1f1.
2. Open Assets/Scenes/ARUCO_WebGL.unity.
3. Target marker is DICT_4X4_50 ID 0.
4. The 3D model starts disabled.
5. When marker ID 0 is detected, WebArucoController calls SetActive(true).
6. When the marker is lost, the model is disabled again.
7. WebGL camera requires HTTPS (or localhost) and browser camera permission.
8. The WebGL template loads OpenCV.js 4.13.0 from docs.opencv.org.
9. This project intentionally does not use OpenCvSharpExtern/native DLLs in WebGL.
