# From the Author
Hi there, I'm Yibo Liu. 

~~I'm facing some uncontrollable challenges right now and don’t have the mood to update this repo. If I can get through this, I will try to complete the repo.~~

Although I am still fighting against witch hunting, I will try to provide updates to this repository before April.

Due to IP policies, we are unable to release a click-and-run version of HIPPo. However, I will provide sufficient details here to help you reproduce a HIPPo-like framework. In particular, the method does not require a pre-built 3D model and can perform 6D pose estimation directly from the first observation.

# Model Weights
HIPPo is a training-free approach. In other words, you only need to download the pre-trained models to construct it.
<table align="center">
    <tr>
        <th>Model</th>
        <th>Function</th>
        <th>Link</th>
    </tr>
    <tr>
        <th>Grounded SAM</th>
        <th>Segmentation</th>
       <th><a href="https://github.com/IDEA-Research/GroundingDINO/releases/download/v0.1.0-alpha/groundingdino_swint_ogc.pth">Swint</a></th>
    </tr>
    <tr>
        <th>Wonder3D</th>
        <th>Multi-view Generation</th>
       <th><a href="https://github.com/xxlong0/Wonder3D?tab=readme-ov-file">GitHub</a></th>
    </tr>
    <tr>
        <th>MASt3R</th>
        <th>3D Model Reconstruction</th>
       <th><a href="https://download.europe.naverlabs.com/ComputerVision/MASt3R/MASt3R_ViTLarge_BaseDecoder_512_catmlpdpt_metric.pth">ViT-Large</a></th>
    </tr>
     <tr>
        <th>FoundationPose</th>
        <th>Object Tracking</th>
       <th><a href="https://drive.google.com/drive/folders/1DFezOAD0oD1BblsXVxqDsl8fj0qzB82i?usp=sharing">FP</a></th>
    </tr>
      <tr>
        <th>InstantMesh (Alternative)</th>
        <th>Multi-view Generation+3D Model Reconstruction</th>
       <th><a href="https://github.com/TencentARC/InstantMesh">GitHub</a></th>
    </tr>
</table>

# Step 1: Object Segmentation


## Acknowledgments
Parts of this project page were adopted from the [Nerfies](https://nerfies.github.io/) page.

