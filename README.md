# Optical-flow-OpenCV

### installation
pip install -r requirements.txt

### Sparse Optical Flow

There is a demo `lucas_kanade.py` script of **Lucas-Kanade** algorithm which can be run with this command:

```
python3 test.py --algorithm lucaskanade --video_path videos/people.mp4
```

### Dense Optical Flow

The wrapper of Dense Optical Flow algorithms `dense_optical.py` can run a couple of OpenCV's algorithm
implementations:

- To start the **Dense Lucas-Kanade** algorithm:
  ```
  python3 test.py --algorithm lucaskanade_dense --video_path videos/people.mp4
  ```
- To start the **Farneback** algorithm:
  ```
  python3 test.py --algorithm farneback --video_path videos/people.mp4
  ```
- To start the **RLOF** algorithm:
  ```
  python3 test.py --algorithm rlof --video_path videos/people.mp4
  ```
