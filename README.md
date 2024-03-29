# A Simple Early Exiting Framework for Accelerated Sampling in Diffusion Models

## Ablation studies on diverse dropping schedules
### 1. Imagnet + DiT
#### 1.1. DDPM solver with 250step
![ddpm_baseline.jpg1](./images/ddpm_250_baseline.png) |![ddpm_ours.jpg2](./images/ddpm_250_ours.png)
--- | --- |

#### 1.2. DDIM solver with 100step
![ddim_baseline.jpg1](./images/ddim_100_baseline.png) |![ddim_ours.jpg2](./images/ddim_100_ours.png)
--- | --- |

#### 1.3. DPM solver with 25step
![dpm_baseline.jpg1](./images/dpm_25_baseline.png) |![dpm_ours.jpg2](./images/dpm_25_ours.png)
--- | --- |

### 2. CelebA + U-ViT
#### 2.1. DPM solver with 50step


## Ablation studies on robustness of sampling steps
### 1. Imagnet + DiT
#### 1.1. DPM solver with 25, 20, 15, 10step
![baseline_robustness.jpg1](./images/baseline_robustness.png)

![ours_robustness.jpg2](./images/ours_robustness.png)

### 2. CelebA + U-ViT
#### 2.1. DPM solver with 25, 20, 15, 10step