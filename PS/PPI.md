在 Photoshop（PS）中，**300 PPI** 是指图像的**像素密度**，即每英寸（inch）内包含的像素数，单位是 **Pixels Per Inch（PPI）**。它是衡量图像分辨率的重要指标，直接影响图像的质量和清晰度。  

---

### **PPI 的意义**  

1. **图像质量**  
   - **高 PPI**：如 300 PPI，表示每英寸内像素更多，图像更细腻，适合高质量打印。  
   - **低 PPI**：如 72 PPI，表示每英寸内像素较少，可能显得模糊或像素化，适合屏幕显示。  

2. **打印效果**  
   - 在印刷领域，通常需要 300 PPI 或更高的分辨率来确保打印出来的图像清晰细腻。  
   - 如果低于 300 PPI，印刷品可能会出现锯齿或模糊。  

3. **屏幕显示**  
   - 屏幕设备通常使用 72 PPI 或 96 PPI，但随着高分辨率屏幕（如 Retina 屏幕）的发展，显示密度可能更高。  
   - 即使图像设置为 300 PPI，在屏幕上不会显著提高显示质量，因屏幕显示更多取决于设备的物理分辨率。  

---

### **300 PPI 在使用中的理解**  

- **实际尺寸与像素总数的关系**  
  图像尺寸不仅由 PPI 决定，还取决于总像素数。例如：  
  - 一个 300 PPI 的图像，如果尺寸为 10x10 英寸，其总像素数为：  
    \[
    300 \, PPI \times 10 \, \text{英寸} = 3000 \, \text{像素（宽/高）}
    \]
    总像素数为 3000 x 3000 = 9,000,000 像素（900 万像素）。  

- **调整 PPI 时需要注意**  
  在 PS 中调整 PPI 时，可能会改变图像的物理尺寸或总像素数。  
  - **重采样（Resample）开启**：PS 会自动增加或减少像素数以匹配新的 PPI。  
  - **重采样关闭**：总像素数不变，但物理尺寸会随 PPI 改变。  

---

### **实际应用场景**  

1. **设计和印刷**  
   - 设计名片、海报等印刷品时，通常设置为 300 PPI。  
   - 如果设计尺寸不足，但 PPI 足够，打印效果仍然清晰。  

2. **屏幕显示**  
   - 如果仅用于网页或屏幕显示，72 PPI 或 96 PPI 即可满足需求，过高的 PPI 可能导致文件体积增大，加载时间增加。  

---

### **总结**  
300 PPI 是图像分辨率的标准单位，特别适用于印刷场景，可确保图像打印效果细腻清晰。在 Photoshop 中合理设置 PPI，可以根据需求在打印质量和文件大小之间取得平衡。