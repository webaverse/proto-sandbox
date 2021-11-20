# Prototype Sandbox Scene
![sdasdas](https://user-images.githubusercontent.com/29487929/142738799-7daf9ea0-988d-41c2-9b88-242e3993eea5.png)

Features:
- Uneven/spiky terrain for movement testing
- Underground and above ground tunnels (can be used for camera pressure tests)

Example scn file: 

```
{
  "objects": [
    {
      "type": "application/light",
      "content": {
        "lightType": "ambient",
        "args": [[255, 255, 255], 0.5]
      }
    },
    {
      "type": "application/light",
      "content": {
        "lightType": "directional",
        "args": [[255, 255, 255], 5],
        "position": [1, 2, 3],
        "shadow": [50, 4096, 0.1, 1000, 0, 0.2]
      }
    },
    {
      "position": [
        0,
        0,
        0
      ],
      "start_url": "https://webaverse.github.io/atmospheric-sky/"
    },
    {
      "position": [
        4,
        0,
        1
      ],
      "quaternion": [
        0,
        0.7071067811865475,
        0,
        0.7071067811865475
      ],
      "start_url": "https://avatar-models.exokit.org/model49.vrm",
      "dynamic": true
    },
    {
      "position": [
        -26,
        0,
        -2
      ],
      "quaternion": [
        0,
        0.7071067811865475,
        0,
        0.7071067811865475
      ],
      "start_url": "https://webaverse.github.io/app/public/avatars/scillia.vrm",
      "dynamic": true
    },
    {
      "position": [
        0,
        0,
        0
      ],
      "physics": true,
      "start_url": "https://webaverse.github.io/proto-sandbox/",
      "dynamic": false
    }
  ]
}

```
