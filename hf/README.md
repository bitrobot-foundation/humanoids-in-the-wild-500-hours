---
pretty_name: "HIW-500: Humanoids In-the-Wild Dataset"
language:
- en
tags:
- robotics
- humanoid
---

# HIW-500: Humanoids In-the-Wild Dataset

https://bitrobot-foundation.github.io/humanoids-in-the-wild-500-hours/

HIW-500: Humanoids In-the-Wild Dataset is a large-scale dataset for whole-body humanoid robot learning in natural home environments. It captures human teleoperation demonstrations on Unitree G1 across real homes in Southeast Asia, where layouts, object states, lighting, clutter, and operator styles vary from episode to episode.

The dataset is designed for research on mobile manipulation, bimanual interaction, long-horizon household skills, imitation learning, and general-purpose robot learning from in-the-wild demonstrations.

## Dataset Overview

- 500+ hours of humanoid robot demonstrations
- 23K+ episodes
- Around 10 TB of data
- 10+ household tasks
- 12 real homes
- 161 subtask labels
- 148K+ subtask annotations

## Data Modalities

Each episode records human whole-body teleoperation of Unitree G1 in real homes. The dataset combines synchronized visual observations, robot states, actions, and metadata.

### Camera Streams

- Head camera: RGB stereo, 480p, 30 FPS
- Wrist camera: RGB, stereo IR, 480p, 30 FPS

### Robot State and Actions

- 29-DoF joint states
- End-effector state
- IMU
- Odometry
- Action traces from human whole-body teleoperation

### Metadata

- Language annotations
- Episode information
- Camera intrinsics and extrinsics

## Dataset Statistics

![Task duration](assets/readme/task_duration_share.png)

![Task episodes](assets/readme/task_episodes.png)

![Average duration](assets/readme/average_duration.png)

## Dataset Access

The dataset is hosted on Hugging Face in two formats:

- Raw ROS bag / MCAP recordings: https://huggingface.co/datasets/BitRobot/HIW-500
- LeRobot format: https://huggingface.co/datasets/BitRobot/HIW-500-LeRobot

## Citation

If you use this dataset, please cite:

```bibtex
@misc{hiw500_2026,
  title={HIW-500: Humanoids In-the-Wild Dataset for Robot Learning},
  author={BitRobot and Unitree and Hugging Face},
  year={2026},
  howpublished={\url{https://bitrobot-foundation.github.io/humanoids-in-the-wild-500-hours/}}
}
```

## Commercial Access and Custom Data

For additional coverage, commercial rights, evaluation data, or custom data collection, [contact us](mailto:contact@bitrobot.ai?subject=Dataset%20Inquiry).
