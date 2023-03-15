1. 生成数据集以及data/rail.yaml文件
2. 修改(hyp.scratch-low.yaml)[data/hyps/hyp.scratch-low.yaml]，其中`component_id`是想要增强的物体在yaml文件中的index，`component_fliplr`是左右翻转的概率
  ```
  component_id: 0
  component_fliplr: 0.2
  ```
