Operator lists
==============

.. Please keep in chronological order when editing
.. csv-table::
    :widths: auto
    :header: "Operator","Android NN","Supported","Remark"

    "AVERAGE_POOL_2D","Y","Y",""
    "ARGMAX","","Y","Only CPU and tensorflow is supported"
    "BATCH_NORM","","Y","Fusion with activation is supported"
    "BATCH_TO_SPACE_ND","Y","Y",""
    "BIAS_ADD","","Y",""
    "CAST","","Y","Only CPU and tensorflow model is supported"
    "CHANNEL_SHUFFLE","","Y",""
    "CONCATENATION","Y","Y","Only support channel axis concatenation"
    "CONV_2D","Y","Y","Fusion with BN and activation layer is supported"
    "DECONV_2D","","Y","Only tensorflow model is supported"
    "DEPTHWISE_CONV_2D","Y","Y","Only multiplier = 1 is supported; Fusion is supported"
    "DEPTH_TO_SPACE","Y","Y",""
    "DEQUANTIZE","Y","Y","Model quantization will be supported later"
    "ELEMENT_WISE","Y","Y","ADD/MUL/DIV/MIN/MAX/NEG/ABS/SQR_DIFF/POW/RSQRT/EQUAL"
    "EMBEDDING_LOOKUP","Y","Y","Only support channel axis concatenation"
    "FLOOR","Y","",""
    "FULLY_CONNECTED","Y","Y",""
    "GROUP_CONV_2D","","","Caffe model with group count = channel count is supported"
    "HASHTABLE_LOOKUP","Y","",""
    "IDENTITY","","Y","Only tensorflow model is supported"
    "L2_NORMALIZATION","Y","",""
    "L2_POOL_2D","Y","",""
    "LOCAL_RESPONSE_NORMALIZATION","Y","Y",""
    "LOGISTIC","Y","Y",""
    "LSH_PROJECTION","Y","",""
    "LSTM","Y","",""
    "MATMUL","","Y",""
    "MAX_POOL_2D","Y","Y",""
    "PAD", "Y","Y",""
    "PSROI_ALIGN","","Y",""
    "PRELU","","Y","Only caffe model is supported"
    "REDUCE_MEAN","Y","Y","Only tensorflow model is supported"
    "RELU","Y","Y",""
    "RELU1","Y","Y",""
    "RELU6","Y","Y",""
    "RELUX","","Y",""
    "RESHAPE","Y","Y","Limited support: only internal use of reshape in composed operations is supported"
    "RESIZE_BILINEAR","Y","Y",""
    "RNN","Y","",""
    "RPN_PROPOSAL_LAYER","","Y",""
    "SHAPE","","Y","Only CPU and tensorflow is supported"
    "STACK","","Y","Only CPU and tensorflow is supported"
    "STRIDEDSLICE","Y","Y","Only CPU and tensorflow is supported"
    "SLICE","","Y","In tensorflow, this op is equivalent to SPLIT; Only support channel axis slice"
    "SOFTMAX","Y","Y",""
    "SPACE_TO_BATCH_ND","Y", "Y",""
    "SPACE_TO_DEPTH","Y","Y",""
    "SQEEZE","Y","Y","Only CPU and tensorflow is supported"
    "SVDF","Y","",""
    "TANH","Y","Y",""
    "TRANSPOSE","Y","Y","Only CPU and tensorflow is supported"
