---
sidebar_label: "Supported Operations"
description: "Check the operations supported by OpenVINO."
---

import Tabs from '@theme/Tabs';
import TabItem from '@theme/TabItem';

# Supported Operations

Here, you will find comprehensive information on operations supported by OpenVINO. The
conformance reports provide operation coverage for inference devices, while the tables list
operations available for all OpenVINO framework frontends.

Data as of OpenVINO 2025.4.1 (December 18, 2025).

**Device-operation conformance reports:**

`````{grid} 1 1 2 2
:gutter: 4

````{grid-item}
```{button-link} ../../_static/conformance_files/conformance_reports/opset_report_omz_static.html
:color: primary
:outline:
:expand:

ops with static shapes only
```
````

````{grid-item}
```{button-link} ../../_static/conformance_files/conformance_reports/opset_report_omz_dynamic.html
:color: primary
:outline:
:expand:

ops including dynamic inputs
```
````
`````

**Operations supported by OpenVINO frontend Frameworks:**

<Tabs>
  <TabItem value="pytorch" label="PyTorch">
  ```{data-table}
  :class: modeldata stripe
  :name: TensorFlow_ops_v1
  :header-rows: 1
  :file: ../../_static/conformance_files/pytorch_ops.csv
  :data-column-hidden: []
  :data-order: [[ 0, "asc" ]]
  :data-page-length: 10
  ```
  </TabItem>
  <TabItem value="tensorflow" label="TensorFlow">
  ```{data-table}
  :class: modeldata stripe
  :name: TensorFlow_ops_v2
  :header-rows: 1
  :file: ../../_static/conformance_files/tensorflow_ops.csv
  :data-column-hidden: []
  :data-order: [[ 0, "asc" ]]
  :data-page-length: 10
  ```
  </TabItem>
  <TabItem value="paddlepaddle" label="PaddlePaddle">
  ```{data-table}
  :class: modeldata stripe
  :name: Paddle_ops
  :header-rows: 1
  :file: ../../_static/conformance_files/paddlepaddle_ops.csv
  :data-column-hidden: []
  :data-order: [[ 0, "asc" ]]
  :data-page-length: 10
  ```
  </TabItem>
  <TabItem value="onnx" label="ONNX">
  | ONNX Supported Operations (standard) | Limitations |
  | --- | --- |
  | Abs |  |
  | Acos |  |
  | Acosh |  |
  | AdaptiveAvgPool2d |  |
  | Add |  |
  | Affine |  |
  | And |  |
  | ArgMax |  |
  | ArgMin |  |
  | Asin |  |
  | Asinh |  |
  | Atan |  |
  | Atanh |  |
  | ATen |  |
  | AveragePool |  |
  | BatchNormalization |  |
  | BitShift |  |
  | BitwiseAnd |  |
  | BitwiseNot |  |
  | BitwiseOr |  |
  | BitwiseXor |  |
  | BlackmanWindow |  |
  | Cast |  |
  | CastLike |  |
  | Ceil |  |
  | Celu |  |
  | Clip |  |
  | Compress |  |
  | Concat |  |
  | Constant |  |
  | ConstantFill |  |
  | ConstantOfShape |  |
  | Conv |  |
  | ConvInteger |  |
  | ConvTranspose |  |
  | Cos |  |
  | Cosh |  |
  | Crop |  |
  | CumSum |  |
  | DepthToSpace |  |
  | DequantizeLinear |  |
  | DFT |  |
  | Div |  |
  | Dropout |  |
  | DynamicQuantizeLinear |  |
  | Einsum |  |
  | Elu |  |
  | Equal |  |
  | Erf |  |
  | Exp |  |
  | Expand |  |
  | EyeLike |  |
  | Flatten |  |
  | Floor |  |
  | Gather |  |
  | GatherElements |  |
  | GatherND |  |
  | Gelu |  |
  | Gemm |  |
  | GlobalAveragePool |  |
  | GlobalLpPool |  |
  | GlobalMaxPool |  |
  | Greater |  |
  | GreaterOrEqual |  |
  | GridSample | Only 4D input tensors are supported. |
  | GroupNormalization |  |
  | GRU |  |
  | HammingWindow |  |
  | HardSigmoid |  |
  | HardSwish |  |
  | Hardmax |  |
  | Identity |  |
  | If |  |
  | ImageScaler |  |
  | InstanceNormalization |  |
  | IsFinite |  |
  | IsInf |  |
  | IsNaN |  |
  | LayerNormalization |  |
  | LeakyRelu |  |
  | Less |  |
  | LessOrEqual |  |
  | Log |  |
  | LogSoftmax |  |
  | Loop |  |
  | LpNormalization |  |
  | LpPool |  |
  | LRN |  |
  | LSTM |  |
  | MatMul |  |
  | MatMulInteger |  |
  | Max |  |
  | MaxPool |  |
  | MaxRoiPool |  |
  | Mean |  |
  | MeanVarianceNormalization |  |
  | Min |  |
  | Mish |  |
  | MMCVRoIAlignRotated |  |
  | Mod |  |
  | Mul |  |
  | Multinomial |  |
  | Neg |  |
  | NMSRotated |  |
  | NonMaxSuppression |  |
  | NonZero |  |
  | Not |  |
  | OneHot |  |
  | Or |  |
  | Pad |  |
  | Pow |  |
  | PRelu |  |
  | QLinearConv |  |
  | QLinearMatMul |  |
  | QuantizeLinear |  |
  | RandomNormal |  |
  | RandomNormalLike |  |
  | RandomUniform |  |
  | RandomUniformLike |  |
  | Range |  |
  | Reciprocal |  |
  | ReduceLogSum |  |
  | ReduceLogSumExp |  |
  | ReduceL1 |  |
  | ReduceL2 |  |
  | ReduceMax |  |
  | ReduceMean |  |
  | ReduceMin |  |
  | ReduceProd |  |
  | ReduceSum |  |
  | ReduceSumSquare |  |
  | Relu |  |
  | Reshape |  |
  | Resize |  |
  | ReverseSequence |  |
  | RMSNormalization |  |
  | RNN |  |
  | RoiAlign |  |
  | RotaryEmbedding |  |
  | Round |  |
  | Scan |  |
  | ScatterElements |  |
  | ScatterND |  |
  | Selu |  |
  | SequenceAt |  |
  | Shape |  |
  | Shrink |  |
  | Sigmoid |  |
  | Sign |  |
  | Sin |  |
  | Sinh |  |
  | Size |  |
  | Slice |  |
  | Softmax |  |
  | Softplus |  |
  | Softsign |  |
  | SpaceToDepth |  |
  | Split |  |
  | SplitToSequence |  |
  | Sqrt |  |
  | Squeeze |  |
  | STFT |  |
  | Sub |  |
  | Sum |  |
  | Swish |  |
  | Tan |  |
  | Tanh |  |
  | ThresholdedRelu |  |
  | Tile |  |
  | TopK |  |
  | Transpose |  |
  | Trilu |  |
  | Unique |  |
  | Unsqueeze |  |
  | Upsample |  |
  | Where |  |
  | Xor |  |

  | ONNX Supported Operations (deprecated) | Limitations |
  | --- | --- |
  | Affine |  |
  | Crop |  |
  | Scatter |  |
  | Upsample |  |

  | ONNX Supported Operations (custom - the org.openvinotoolkit Domain) | Limitations |
  | --- | --- |
  | DeformableConv2D |  |
  | DetectionOutput |  |
  | ExperimentalDetectronDetectionOutput |  |
  | ExperimentalDetectronGenerateProposalsSingleImage |  |
  | ExperimentalDetectronGroupNorm |  |
  | ExperimentalDetectronPriorGridGenerator |  |
  | ExperimentalDetectronROIFeatureExtractor |  |
  | ExperimentalDetectronTopKROIs |  |
  | FakeQuantize |  |
  | GroupNorm |  |
  | Normalize |  |
  | PriorBox |  |
  | PriorBoxClustered |  |
  | Swish |  |

  | ONNX Supported Operations (custom - com.microsoft Domain) | Limitations |
  | --- | --- |
  | Attention |  |
  | Bias\_Add |  |
  | BiasGelu |  |
  | Dynamic\_Quantize\_MatMul |  |
  | EmbedLayerNormalization |  |
  | Fast\_Gelu |  |
  | Fused\_Conv |  |
  | FusedGemm |  |
  | FusedMatMul |  |
  | GatherBlockQuantized |  |
  | GroupQueryAttention |  |
  | MatMulIntegerToFloat |  |
  | MatMulNBits |  |
  | Pad |  |
  | QLinearActivation |  |
  | QLinearAdd |  |
  | QLinearMul |  |
  | QuickGelu |  |
  | Range |  |
  | SimplifiedLayerNormalization |  |
  | SkipLayerNormalization |  |
  | SkipSimplifiedLayerNormalization |  |
  </TabItem>
  <TabItem value="tensorflow-lite" label="TensorFlow Lite">
  | TensorFlow Lite Supported Operations | Limitations |
  | --- | --- |
  | ABS |  |
  | ADD |  |
  | ADD\_N |  |
  | ARG\_MAX |  |
  | ARG\_MIN |  |
  | AVERAGE\_POOL\_2D |  |
  | BATCH\_MATMUL |  |
  | BATCH\_TO\_SPACE\_ND |  |
  | BROADCAST\_ARGS |  |
  | BROADCAST\_TO |  |
  | CAST |  |
  | CEIL |  |
  | COMPLEX\_ABS | Supported in a specific pattern with RFFT2D |
  | CONCATENATION |  |
  | CONV\_2D |  |
  | COS |  |
  | DEPTH\_TO\_SPACE |  |
  | DEPTHWISE\_CONV\_2D |  |
  | DEQUANTIZE |  |
  | DIV |  |
  | ELU |  |
  | EQUAL |  |
  | EXP |  |
  | EXPAND\_DIMS |  |
  | FILL |  |
  | FLOOR |  |
  | FLOOR\_DIV |  |
  | FLOOR\_MOD |  |
  | FULLY\_CONNECTED |  |
  | GATHER |  |
  | GATHER\_ND |  |
  | GREATER |  |
  | GREATER\_EQUAL |  |
  | HARD\_SWISH |  |
  | L2\_NORMALIZATION |  |
  | LEAKY\_RELU |  |
  | LESS |  |
  | LESS\_EQUAL |  |
  | LOG |  |
  | LOG\_SOFTMAX |  |
  | LOGICAL\_AND |  |
  | LOGICAL\_NOT |  |
  | LOGICAL\_OR |  |
  | LOGISTIC |  |
  | MATRIX\_DIAG |  |
  | MAX\_POOL\_2D |  |
  | MAXIMUM |  |
  | MEAN |  |
  | MINIMUM |  |
  | MIRROR\_PAD |  |
  | MUL |  |
  | NEG |  |
  | NOT\_EQUAL |  |
  | ONE\_HOT |  |
  | PACK |  |
  | PAD |  |
  | PADV2 |  |
  | POW |  |
  | PRELU |  |
  | QUANTIZE |  |
  | RANGE |  |
  | RANK |  |
  | REDUCE\_ALL |  |
  | REDUCE\_ANY |  |
  | REDUCE\_MAX |  |
  | REDUCE\_MIN |  |
  | REDUCE\_PROD |  |
  | RELU |  |
  | RELU6 |  |
  | RESHAPE |  |
  | RESIZE\_BILINEAR |  |
  | RESIZE\_NEAREST\_NEIGHBOR |  |
  | REVERSE\_V2 |  |
  | RFFT2D | Supported in a specific pattern with COMPLEX\_ABS |
  | ROUND |  |
  | RSQRT |  |
  | SCATTER\_ND |  |
  | SEGMENT\_SUM |  |
  | SELECT |  |
  | SELECT\_V2 |  |
  | SHAPE |  |
  | SIGN |  |
  | SIN |  |
  | SLICE |  |
  | SOFTMAX |  |
  | SPACE\_TO\_BATCH\_ND |  |
  | SPACE\_TO\_DEPTH |  |
  | SPLIT |  |
  | SPLIT\_V |  |
  | SQRT |  |
  | SQUARE |  |
  | SQUARED\_DIFFERENCE |  |
  | SQUEEZE |  |
  | STRIDED\_SLICE |  |
  | SUB |  |
  | SUM |  |
  | TANH |  |
  | TILE |  |
  | TOPK\_V2 |  |
  | TRANSPOSE |  |
  | TRANSPOSE\_CONV |  |
  | UNIQUE |  |
  | UNPACK |  |
  | WHERE |  |
  | ZEROS\_LIKE |  |
  </TabItem>
  <TabItem value="tensorflow2-keras" label="TensorFlow2 Keras">
  | TensorFlow 2 Keras Supported Operations | Limitations |
  | --- | --- |
  | ActivityRegularization |  |
  | Add |  |
  | AdditiveAttention |  |
  | AlphaDropout |  |
  | Attention |  |
  | Average |  |
  | AveragePooling1D |  |
  | AveragePooling2D |  |
  | AveragePooling3D |  |
  | BatchNormalization |  |
  | Bidirectional |  |
  | Concatenate |  |
  | Conv1D |  |
  | Conv1DTranspose | Not supported if `dilation` is not equal to 1. |
  | Conv2D |  |
  | Conv2DTranspose |  |
  | Conv3D |  |
  | Conv3DTranspose |  |
  | Cropping1D |  |
  | Cropping2D |  |
  | Cropping3D |  |
  | Dense |  |
  | DenseFeatures | Not supported for categorical and crossed features. |
  | DepthwiseConv2D |  |
  | Dot |  |
  | Dropout |  |
  | ELU |  |
  | Embedding |  |
  | Flatten |  |
  | GRU |  |
  | GRUCell |  |
  | GaussianDropout |  |
  | GaussianNoise |  |
  | GlobalAveragePooling1D |  |
  | GlobalAveragePooling2D |  |
  | GlobalAveragePooling3D |  |
  | GlobalMaxPool1D |  |
  | GlobalMaxPool2D |  |
  | GlobalMaxPool3D |  |
  | LSTM |  |
  | LSTMCell |  |
  | Lambda |  |
  | LayerNormalization |  |
  | LeakyReLU |  |
  | LocallyConnected1D |  |
  | LocallyConnected2D |  |
  | MaxPool1D |  |
  | MaxPool2D |  |
  | MaxPool3D |  |
  | Maximum |  |
  | Minimum |  |
  | Multiply |  |
  | PReLU |  |
  | Permute |  |
  | RNN | Not supported for some custom cells. |
  | ReLU |  |
  | RepeatVector |  |
  | Reshape |  |
  | Roll |  |
  | SeparableConv1D |  |
  | SeparableConv2D |  |
  | SimpleRNN |  |
  | SimpleRNNCell |  |
  | Softmax |  |
  | SpatialDropout1D |  |
  | SpatialDropout2D |  |
  | SpatialDropout3D |  |
  | StackedRNNCells |  |
  | Subtract |  |
  | ThresholdedReLU |  |
  | TimeDistributed |  |
  | UpSampling1D |  |
  | UpSampling2D |  |
  | UpSampling3D |  |
  | ZeroPadding1D |  |
  | ZeroPadding2D |  |
  | ZeroPadding3D |  |
  </TabItem>
</Tabs>
