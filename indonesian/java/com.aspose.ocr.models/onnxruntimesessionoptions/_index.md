---
title: "OnnxRuntimeSessionOptions"
second_title: "Referensi API Aspose.OCR untuk Java"
description: "Opsi konfigurasi untuk membuat ONNX InferenceSession"
type: docs
weight: 20
url: /id/java/com.aspose.ocr.models/onnxruntimesessionoptions/
---

**Inheritance:**
java.lang.Object
```
public class OnnxRuntimeSessionOptions
```

Opsi konfigurasi untuk membuat ONNX InferenceSession. Kami menyarankan untuk mempertahankan nilai default yang dioptimalkan kecuali Anda sangat yakin dengan modifikasi tersebut. Untuk detail teknis, lihat dokumentasi ONNX Runtime.
## Konstruktor

| Konstruktor | Deskripsi |
| --- | --- |
| [OnnxRuntimeSessionOptions()](#OnnxRuntimeSessionOptions) |  |
## Bidang

| Bidang | Deskripsi |
| --- | --- |
| [enableCpuMemArena](#enableCpuMemArena) | Mengaktifkan atau menonaktifkan alokator arena memori CPU yang digunakan oleh ONNX Runtime. |
| [enableMemoryPattern](#enableMemoryPattern) | Mengaktifkan atau menonaktifkan optimasi pola memori untuk tensor input. |
| [executionMode](#executionMode) | Mode eksekusi untuk sesi. |
| [graphOptimizationLevel](#graphOptimizationLevel) | Tingkat optimasi grafik untuk sesi. |
| [interOpNumThreads](#interOpNumThreads) | Jumlah thread untuk menjalankan beberapa operasi secara paralel. |
| [intraOpNumThreads](#intraOpNumThreads) | Jumlah thread untuk satu operasi. |


### OnnxRuntimeSessionOptions() {#OnnxRuntimeSessionOptions}
```
public OnnxRuntimeSessionOptions()
```


### enableCpuMemArena {#enableCpuMemArena}
```
public static boolean enableCpuMemArena
```


Mengaktifkan atau menonaktifkan alokator arena memori CPU yang digunakan oleh ONNX Runtime. Ketika diaktifkan, memori dipool dan digunakan kembali untuk kinerja yang lebih baik, tetapi dapat menyebabkan peningkatan konsumsi memori dalam skenario multi-thread. Nonaktifkan untuk mengurangi penggunaan memori puncak dengan mengorbankan kinerja.

### enableMemoryPattern {#enableMemoryPattern}
```
public static boolean enableMemoryPattern
```


Mengaktifkan atau menonaktifkan optimisasi pola memori untuk tensor masukan. Saat diaktifkan, ONNX Runtime menyimpan pola alokasi memori untuk eksekusi yang lebih cepat, tetapi dapat meningkatkan penggunaan memori untuk bentuk masukan yang dinamis. Nonaktifkan jika masukan sangat bervariasi atau untuk mengurangi jejak memori.

### executionMode {#executionMode}
```
public static ExecutionModeOnnx executionMode
```


Mode eksekusi untuk sesi. Secara default, operator dieksekusi secara bersamaan, bila memungkinkan.

### graphOptimizationLevel {#graphOptimizationLevel}
```
public static GraphOptimizationLevelOnnx graphOptimizationLevel
```


Tingkat optimisasi grafik untuk sesi. Secara default, semua optimisasi yang tersedia diaktifkan untuk kinerja maksimum.

### interOpNumThreads {#interOpNumThreads}
```
public static int interOpNumThreads
```


Jumlah thread untuk menjalankan beberapa operasi secara paralel. Jika eksekusi berurutan diaktifkan, nilai ini diabaikan.

### intraOpNumThreads {#intraOpNumThreads}
```
public static int intraOpNumThreads
```


Jumlah thread untuk satu operasi.