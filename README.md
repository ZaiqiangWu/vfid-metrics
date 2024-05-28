# VFID Metrics

This repository is modified from [fid-metrics](https://github.com/npurson/fid-metrics) and provides a toolkit for computing Video Fréchet Inception Distance (VFID) metrics, widely utilized for assessing the quality of generative models in the fields of video generation.

## Installation

```bash
pip install -r requirements.txt
```

## Usage


0. **Setup**

    Users should create a `weights` folder and place weights `i3d.pt` and `resnext-101.pth` in it. (weights could be found in [GoogleDrive](https://drive.google.com/drive/folders/1hYfZPkqF8GX9e3KOg28NPOe9CPG-Fyk6?usp=drive_link))
    
    Remember to modify `configs/config.yaml` according to your needs.

1. **Calculating FID/FVD**

    ```shell
    python fid_metrics/main.py
    ```

## Acknowledgements

The code in this repository is based on [pytorch-fid](https://github.com/mseitzer/pytorch-fid) and [fvd-comparison](https://github.com/universome/fvd-comparison).

## License

Released under the [MIT](LICENSE) License.
