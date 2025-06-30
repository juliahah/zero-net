# Energy Analysis

This document analyzes the energy consumption of a standard 4K YouTube video compared to content hosted on the Zero-Net platform.

Measurements were conducted using a **Raspberry Pi 4** running **Raspberry Pi OS (64-bit)**. Energy usage was recorded using a **wattmeter**, with all content displayed in **Chromium browser**.

---

## Methodology

Energy measurements were collected across three scenarios:

1. **Idle Baseline**
2. **Streaming a 4K YouTube Video**  
   Test video: [YouTube 4K Sample](https://www.youtube.com/watch?v=LXb3EKWsInQ)
3. **Streaming a Zero-Net Demo**  
   Content: [SlowFrame Demo](https://disinnovation.org/slowframe/index.php#/slide-0)

- **Duration:** Each session lasted 2 minutes.
- **Sampling Rate:** Power readings were taken every 15 seconds.
- **Data File:** See `computer-energy.csv` for full data.

---

## Results

| Scenario        | Average Power (W) | Excess Power (vs Idle) |
|-----------------|-------------------|-------------------------|
| Idle            | 2.40 W            | –                       |
| YouTube 4K      | 5.03 W            | +2.63 W                 |
| Zero-Net Demo   | 3.96 W            | +1.56 W                 |

---

## Conclusion

The Zero-Net audiovisual demo consumed noticeably less energy than streaming a 4K YouTube video:

>  Roughly **1.1 W less** than YouTube 4K