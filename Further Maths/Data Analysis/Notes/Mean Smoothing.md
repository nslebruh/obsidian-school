# Mean Smoothing



• Mean Smoothing is a technique used to reduce the amount of noise in a signal or image. 
• It is a form of low-pass filtering, which means it reduces high-frequency components of a signal. 
• It works by replacing each data point with the average of the neighbouring points.
• Formulas: 
  • Mean Smoothing: $f_s(x) = \frac{1}{2k+1} \sum_{i=-k}^k f(x+i)$
  • Weighted Mean Smoothing: $f_s(x) = \frac{\sum_{i=-k}^k w_i f(x+i)}{\sum_{i=-k}^k w_i}$
  • Where $w_i$ are the weights assigned to each data point.