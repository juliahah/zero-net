# Datatransfer Analysis: YouTube 4K vs Zero-net Experiments

This report compares the data transfer  of a standard 4K YouTube video with several experimental media formats of Zero net.

Measurements were taken using the DevTools in Chrome. Data where taken from the Network tab.  

---

## 1. YouTube 4K Video

Test video: [YouTube 4K Sample](https://www.youtube.com/watch?v=LXb3EKWsInQ)

To obtain a reliable average, the video was measured over 1 and 2 minutes across three sessions on the 15th of June. The resulting data is available in the file: `data-transfer-yt.csv`.


For broader context, an additional dataset was referenced from Android Authority:  
[How much data does YouTube use?](https://www.androidauthority.com/how-much-data-does-youtube-use-964560/)  
This comparison data is included in: `bitrate-yt-androidauthority.csv`.

In our own measurement, the 2-minute 4K YouTube playback transferred approximately 531 MB.  
➤ Average per minute: **265.5 MB**  
This aligns with Android Authority’s reference range for 4K streaming: **95–385 MB/min**

---

## 2. Zero-net Experiments
In comparison, we measured a range of audiovisual experiments hosted on Zero-Net platforms. Where data transfer varied over time, three sessions were conducted and averaged; otherwise, a single result is provided. See: `data-transfer-zero-net.csv`

---


## 3. Comparative Results 
This section presents a selection of Zero-Net formats and their data usage compared to the YouTube 4K reference.

**YouTube 4K (measured average):**  
`265.5 MB per minute (100%)`

---

### Zero Pixel Video Interview  
| Mode                  | Data/min | % of YouTube 4K |
|-----------------------|----------|-----------------|
| Visual only           | 1.6 MB   | 0.60%           |
| + Audio & Subtitles   | +0.4 MB  | 0.76% total     |

---

### Face Fade Interview 
| Mode                  | Data/min | % of YouTube 4K |
|-----------------------|----------|-----------------|
| Visual only           | 0.223 MB | 0.08%           |
| + Audio & Subtitles   | +0.4 MB  | 0.23% total     |

---

### Climate Map  
| Mode                  | Data/min | % of YouTube 4K |
|-----------------------|----------|-----------------|
| Visual only           | 0.442 MB | 0.16%           |
| + Audio & Subtitles   | +0.4 MB  | 0.33% total     |

---

### Noise Video Synthesizer  
| Mode                  | Data/min | % of YouTube 4K |
|-----------------------|----------|-----------------|
| Visual only           | 0.809 MB | 0.30%           |
| + Audio & Subtitles   | +0.4 MB  | 0.45% total     |

---

### Text-Based Animation  
| Mode                  | Data/min | % of YouTube 4K |
|-----------------------|----------|-----------------|
| Visual only           | 0.419 MB | 0.15%           |
| + Audio & Subtitles   | +0.4 MB  | 0.30% total     |

---

### 3D Model  
| Mode                  | Data/min | % of YouTube 4K |
|-----------------------|----------|-----------------|
| Visual only           | 0.616 MB | 0.23%           |
| + Audio & Subtitles   | +0.4 MB  | 0.38% total     |

Zero-Net-based experiments demonstrate a radically reduced data footprint:

> Most use **less than 1%** of the bandwidth of a standard YouTube 4K video

> typically around **0.1% to 0.5%**, including both visuals and optional audio/subtitles.