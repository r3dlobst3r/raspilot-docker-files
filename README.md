# This is where the stock versions of dynamic files needed by docker-raspilot
You will still need to unzip model to the modles directory in this repo.

Temp:

```docker run --privileged --mount type=bind,source=/home/ubuntu/raspilot-docker-files/kegman.json,target=/home/ubuntu/kegman.json --mount type=bind,source=/home/ubuntu/raspilot-docker-files/models,target=/home/ubuntu/raspilot/models --mount type=bind,source=/home/ubuntu/raspilot-docker-files/upload,target=/data/upload --mount type=bind,source=/home/ubuntu/raspilot-docker-files/gernby.json,target=/home/ubuntu/raspilot/selfdrive/gernby.json --mount type=bind,source=/home/ubuntu/raspilot-docker-files/CalibrationParams,target=/data/params/d/CalibrationParams -it r3dlobst3r/docker-raspilot-tq```
