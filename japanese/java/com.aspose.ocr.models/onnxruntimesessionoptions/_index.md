---
title: "OnnxRuntimeSessionOptions"
second_title: "Java 用 Aspose.OCR API リファレンス"
description: "ONNX InferenceSession を作成するための構成オプション"
type: docs
weight: 20
url: /ja/java/com.aspose.ocr.models/onnxruntimesessionoptions/
---

**Inheritance:**
java.lang.Object
```
public class OnnxRuntimeSessionOptions
```

ONNX InferenceSession を作成するための構成オプションです。変更に絶対的な自信がない限り、最適化されたデフォルト設定を維持することを推奨します。技術的な詳細については、ONNX Runtime のドキュメントを参照してください。
## コンストラクタ

| コンストラクタ | 説明 |
| --- | --- |
| [OnnxRuntimeSessionOptions()](#OnnxRuntimeSessionOptions) |  |
## フィールド

| フィールド | 説明 |
| --- | --- |
| [enableCpuMemArena](#enableCpuMemArena) | ONNX Runtime が使用する CPU メモリアリーナアロケータを有効化または無効化します。 |
| [enableMemoryPattern](#enableMemoryPattern) | 入力テンソルに対するメモリパターン最適化を有効化または無効化します。 |
| [executionMode](#executionMode) | セッションの実行モード。 |
| [graphOptimizationLevel](#graphOptimizationLevel) | セッションのグラフ最適化レベル。 |
| [interOpNumThreads](#interOpNumThreads) | 複数の操作を並列で実行するためのスレッド数。 |
| [intraOpNumThreads](#intraOpNumThreads) | 単一の操作に使用するスレッド数。 |


### OnnxRuntimeSessionOptions() {#OnnxRuntimeSessionOptions}
```
public OnnxRuntimeSessionOptions()
```


### enableCpuMemArena {#enableCpuMemArena}
```
public static boolean enableCpuMemArena
```


ONNX Runtime が使用する CPU メモリアリーナアロケータを有効化または無効化します。有効にすると、メモリがプールされ再利用されパフォーマンスが向上しますが、マルチスレッド環境ではメモリ消費が増加する可能性があります。パフォーマンスを犠牲にしてピークメモリ使用量を削減したい場合は無効にしてください。

### enableMemoryPattern {#enableMemoryPattern}
```
public static boolean enableMemoryPattern
```


入力テンソルに対するメモリパターン最適化を有効化または無効化します。有効にすると、ONNX Runtime は高速実行のためにメモリ割り当てパターンをキャッシュしますが、動的入力形状に対してメモリ使用量が増加する可能性があります。入力が大きく変動する場合やメモリフットプリントを削減したい場合は無効にしてください。

### executionMode {#executionMode}
```
public static ExecutionModeOnnx executionMode
```


セッションの実行モードです。デフォルトでは、可能な限り演算子が同時に実行されます。

### graphOptimizationLevel {#graphOptimizationLevel}
```
public static GraphOptimizationLevelOnnx graphOptimizationLevel
```


セッションのグラフ最適化レベルです。デフォルトでは、最大のパフォーマンスを得るために利用可能なすべての最適化が有効になっています。

### interOpNumThreads {#interOpNumThreads}
```
public static int interOpNumThreads
```


複数の操作を並列で実行するためのスレッド数です。シーケンシャル実行が有効な場合、この値は無視されます。

### intraOpNumThreads {#intraOpNumThreads}
```
public static int intraOpNumThreads
```


単一の操作に使用するスレッド数。