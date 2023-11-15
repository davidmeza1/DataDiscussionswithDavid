[𝐔𝐧𝐥𝐞𝐚𝐬𝐡𝐢𝐧𝐠 𝐑𝐞𝐚𝐥𝐢𝐬𝐦: 𝐌𝐚𝐬𝐭𝐞𝐫𝐢𝐧𝐠 𝐒𝐲𝐧𝐭𝐡𝐞𝐭𝐢𝐜 𝐓𝐚𝐛𝐮𝐥𝐚𝐫 𝐃𝐚𝐭𝐚 𝐆𝐞𝐧𝐞𝐫𝐚𝐭𝐢𝐨𝐧 𝐰𝐢𝐭𝐡 𝐂𝐓𝐆𝐀𝐍 𝐚𝐧𝐝 𝐒𝐃𝐕 𝐏𝐲𝐭𝐡𝐨𝐧 𝐋𝐢𝐛𝐫𝐚𝐫𝐢𝐞𝐬 ](https://www.linkedin.com/posts/maryammiradi_machinelearning-artificialintelligence-ai-activity-7087373272035516417-GWyy/?utm_source=share&utm_medium=member_ios) 

[Sythetic Data Vault Project](https://github.com/sdv-dev)

[CTGAN](https://github.com/sdv-dev/CTGAN)

Generative Adversarial Networks (GANs) are powerful for generating realistic synthetic Tabular data but many GANs are only suitable for Images. Why?  
  
ℂ𝕙𝕒𝕝𝕝𝕖𝕟𝕘𝕖𝕤 𝕠𝕗 𝔾𝕖𝕟𝕖𝕣𝕒𝕥𝕚𝕟𝕘 𝕊𝕪𝕟𝕥𝕙𝕖𝕥𝕚𝕔 𝕋𝕒𝕓𝕦𝕝𝕒𝕣 𝔻𝕒𝕥𝕒:  
  
🅞 Mixed data types of discrete and continuous columns.  
  
🅞 Non-Gaussian distributions of Continuous values in tabular data  
  
🅞 Multimodal distributions of continuous columns.  
  
🅞 Sparse one-hot-encoded vectors  
  
🅞 Highly imbalanced categorical columns  
  
𝔼𝕩𝕚𝕤𝕥𝕚𝕟𝕘 𝔾𝔸ℕ𝕤/𝕍𝔸𝔼 𝕗𝕠𝕣 𝕋𝕒𝕓𝕦𝕝𝕒𝕣 𝔻𝕒𝕥𝕒:  
  
There are a few GANs, specially the one for time-series medical records such as medGAN, ehrGAN, tableGAN and PATE-GAN.  
Next to these, there are also types of variational autoencoder (VAE) like TVAE to be used.

ℂ𝕠𝕟𝕕𝕚𝕥𝕚𝕠𝕟𝕒𝕝 𝕋𝕒𝕓𝕦𝕝𝕒𝕣 𝔾𝔸ℕ (ℂ𝕋𝔾𝔸ℕ):  
  
CTGANs seems to be the ideal solution. It has the following properties:  
  
🅘 mode-specific normalization  
🅘 architectural changes  
🅘 addressing data imbalance by employing a conditional generator and training-by-sampling  
🅘 performs significantly better than other GANs  
  
𝐖𝐡𝐞𝐫𝐞 𝐭𝐨 𝐬𝐭𝐚𝐫𝐭? 𝐀𝐥𝐥 𝐏𝐲𝐭𝐡𝐨𝐧 𝐥𝐢𝐛𝐫𝐚𝐫𝐢𝐞𝐬 𝐫𝐞𝐥𝐚𝐭𝐞𝐝 𝐭𝐨 𝐒𝐃𝐕 𝐩𝐫𝐨𝐣𝐞𝐜𝐭 𝐢𝐬 𝐚 𝐠𝐫𝐞𝐚𝐭 𝐬𝐭𝐚𝐫𝐭𝐢𝐧𝐠 𝐩𝐨𝐢𝐧𝐭.  
  
📚 Synthetic Data Vault (SDV)  
  
CTGANs is a part of SDV library. SDV is a Python library for creating tabular synthetic data. The SDV uses a variety of machine learning algorithms to learn patterns from your real data and emulate them in synthetic data.  
  
  
📚 Synthetic Data Gym (SDGym)  
  
SDGym is a benchmarking framework for modeling and generating synthetic data. Measure performance and memory usage across different synthetic data modeling techniques – classical statistics, deep learning and more!  
  
📚 SDMetrics  
  
SDMetrics library evaluates synthetic data by comparing it to the real data that you're trying to mimic. It includes a variety of metrics to capture different aspects of the data, for example quality and privacy.

📚 Copulas  
  
Copulas is a Python library for modeling multivariate distributions and sampling from them using copula functions. Given a table of numerical data, use Copulas to learn the distribution and generate new synthetic data following the same statistical properties.  
  
📚 RDT (Reversible Data Transforms)  
  
RDT is a Python library that transforms raw data into fully numerical data, ready for data science. The transforms are reversible, allowing you to convert from numerical data back into your original format.  
  
📚 DeepEcho  
  
DeepEcho is a Synthetic Data Generation Python library for mixed-type, multivariate time series.