```
├── anchor_generators  # generate anchors
│   ├── grid_anchor_generator.py                         # generates grid anchors on the fly as faster rcnn
│   ├── multiple_grid_anchor_generator.py # generates grid andros on the fly corresponding to multi CNN layers as SSD
│
├── box_coders    
│   ├── faster_rcnn_box_coder.py
│   ├── keypoint_box_coder.py
│   ├── mean_stddev_box_coder.py
│   ├── square_box_coder.py
│
├── builders
│   ├── anchor_generator_builder.py
│   ├── box_coder_builder.py
│   ├── box_predictor_builder.py
│   ├── hyperparams_builder.py
│   ├── image_resizer_builder.py
│   ├── input_reader_builder.py
│   ├── losses_builder.py
│   ├── matcher_builder.py
│   ├── model_builder.py
│   ├── optimizer_builder.py
│   ├── post_processing_builder.py
│   ├── preprocessor_builder.py
│   ├── region_similarity_calculator_builder.py
├── core
│   ├── anchor_generator.py
│   ├── balanced_positive_negative_sampler.py
│   ├── batcher.py
│   ├── box_coder.py
│   ├── box_list_ops.py
│   ├── box_list.py
│   ├── box_predictor.py
│   ├── data_decoder.py
│   ├── keypoint_ops.py
│   ├── losses.py
│   ├── matcher.py
│   ├── minibatch_sampler.py
│   ├── model.py
│   ├── post_processing.py
│   ├── prefetcher.py
│   ├── preprocessor.py
│   ├── region_similarity_calculator.py
│   ├── standard_fields.py
│   ├── target_assigner.py
├── create_pascal_tf_record.py
├── create_pet_tf_record.py
├── data
│   ├── mscoco_label_map.pbtxt
│   ├── pascal_label_map.pbtxt
│   ├── pet_label_map.pbtxt
│   ├── pet_train.record
│   └── pet_val.record
├── data_decoders
│   ├── tf_example_decoder.py
├── eval.py
├── evaluator.py
├── eval_util.py
├── exporter.py
├── export_inference_graph.py
├── g3doc
│   ├── configuring_jobs.md
│   ├── defining_your_own_model.md
│   ├── detection_model_zoo.md
│   ├── exporting_models.md
│   ├── file_structure.md
│   ├── img
│   ├── installation.md
│   ├── preparing_inputs.md
│   ├── running_locally.md
│   ├── running_notebook.md
│   ├── running_on_cloud.md
│   ├── running_pets.md
│   └── using_your_own_dataset.md
├── matchers
│   ├── argmax_matcher.py
│   ├── bipartite_matcher.py
├── meta_architectures
│   ├── faster_rcnn_meta_arch.py
│   ├── faster_rcnn_meta_arch_test_lib.py
│   ├── rfcn_meta_arch.py
│   ├── ssd_meta_arch.py
├── mobile_net_net
│   └── events.out.tfevents.1506430186.dl
├── models
│   ├── faster_rcnn_inception_resnet_v2_feature_extractor.py
│   ├── faster_rcnn_resnet_v1_feature_extractor.py
│   ├── feature_map_generators.py
│   ├── model
│   ├── ssd_inception_v2_feature_extractor.py
│   ├── ssd_mobilenet_v1_feature_extractor.py
├── object_detection_tutorial.ipynb
├── protos
│   ├── anchor_generator.proto
│   ├── argmax_matcher.proto
│   ├── bipartite_matcher.proto
│   ├── box_coder.proto
│   ├── box_predictor.proto
│   ├── eval.proto
│   ├── faster_rcnn_box_coder.proto
│   ├── faster_rcnn.proto
│   ├── grid_anchor_generator.proto
│   ├── hyperparams.proto
│   ├── image_resizer.proto
│   ├── input_reader.proto
│   ├── losses.proto
│   ├── matcher.proto
│   ├── mean_stddev_box_coder.proto
│   ├── model.proto
│   ├── optimizer.proto
│   ├── pipeline.proto
│   ├── post_processing.proto
│   ├── preprocessor.proto
│   ├── region_similarity_calculator.proto
│   ├── square_box_coder.proto
│   ├── ssd_anchor_generator.proto
│   ├── ssd.proto
│   ├── string_int_label_map.proto
│   └── train.proto
│   └── trainer.cpython-35.pyc
├── README.md
├── samples
│   ├── cloud
│   └── configs
├── ssd_mobilenet_v1_coco_11_06_2017
│   └── frozen_inference_graph.pb
├── ssd_mobilenet_v1_coco_11_06_2017.tar.gz
├── test_images
│   ├── car.png
│   ├── image1.jpg
│   ├── image2.jpg
│   ├── image_info.txt
│   └── Selection_209.png
├── trainer.py
├── train.py
└── utils
    ├── category_util.py
    ├── dataset_util.py
    ├── label_map_util.py
    ├── learning_schedules.py
    ├── metrics.py
    ├── np_box_list_ops.py
    ├── np_box_list.py
    ├── np_box_ops.py
    ├── object_detection_evaluation.py
    ├── ops.py
    ├── per_image_evaluation.py
    ├── shape_utils.py
    ├── static_shape.py
    ├── test_utils.py
    ├── variables_helper.py
    ├── visualization_utils.py
```