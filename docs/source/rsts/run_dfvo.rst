---------
Run DF-VO
---------

.. _run-dfvo:

    .. FIXME: update example 

    .. code-block:: shell

        # Example 1: run default kitti setup
        python apis/run.py -d options/kitti/default_configuration.yml  

        # Example 2: Run custom kitti setup
        # kitti_default_configuration.yml and kitti_stereo_0.yml are merged
        python apis/run.py -d options/kitti/default_configuration.yml -c options/kitti/kitti_stereo_0.yml  