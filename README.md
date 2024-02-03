<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div align="center" dir="auto">
<h1 tabindex="-1" dir="auto"><a id="user-content-instantid-zero-shot-identity-preserving-generation-in-seconds" class="anchor" aria-hidden="true" tabindex="-1" href="#instantid-zero-shot-identity-preserving-generation-in-seconds"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">InstantID：几秒钟内零次身份保存生成</font></font></h1>
<p dir="auto"><a href="https://github.com/wangqixun"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">王启勋</font></font></strong></a><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">12</font></font></sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ·</font></font><a href="https://huggingface.co/baymin0220" rel="nofollow"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">徐白</font></font></strong></a><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">12</font></font></sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ·</font></font><a href="https://haofanwang.github.io/" rel="nofollow"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">王浩帆</font></font></strong></a><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">12*</font></font></sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ·</font></font><a href="https://github.com/ZekuiQin"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">秦泽奎</font></font></strong></a><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">12</font></font></sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> ·</font></font><a href="https://antonioo-c.github.io/" rel="nofollow"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">陈安东尼</font></font></strong></a><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">123</font></font></sup></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">华夏黎</font></font><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2</font></font></sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> · 徐唐</font></font><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2</font></font></sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> · 姚虎</font></font><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2</font></font></sup></p>
<p dir="auto"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1</font></font></sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> InstantX 团队 · </font></font><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2</font></font></sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">小红书公司 · </font></font><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">3</font></font></sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">北京大学</font></font></p>
<p dir="auto"><sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">*</font></font></sup><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">通讯作者</font></font></p>
<p dir="auto"><a href="https://instantid.github.io/" rel="nofollow"><img src="https://camo.githubusercontent.com/6a9d6a4500b31d41e107a6677ae561aca05e5c710e593466e10c6dedf2fd4923/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f50726f6a6563742d506167652d677265656e" data-canonical-src="https://img.shields.io/badge/Project-Page-green" style="max-width: 100%;"></a>
<a href="https://arxiv.org/abs/2401.07519" rel="nofollow"><img src="https://camo.githubusercontent.com/f39e225802c64460d7b6cd1eaaf8f22e68682d9d232ed8a9c4521729f9fef1d9/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f546563686e697175652d5265706f72742d726564" data-canonical-src="https://img.shields.io/badge/Technique-Report-red" style="max-width: 100%;"></a>
<a href="https://huggingface.co/papers/2401.07519" rel="nofollow"><img src="https://camo.githubusercontent.com/4d0418102eca066e16a4cc55c86db55ddacf2226757d56d7f985376f26b2deb5/68747470733a2f2f696d672e736869656c64732e696f2f7374617469632f76313f6c6162656c3d5061706572266d6573736167653d48756767696e676661636526636f6c6f723d6f72616e6765" data-canonical-src="https://img.shields.io/static/v1?label=Paper&amp;message=Huggingface&amp;color=orange" style="max-width: 100%;"></a>
<a href="https://github.com/InstantID/InstantID"><img src="https://camo.githubusercontent.com/86f04cb467a481b438b4c63b3a9ec632aa11a50733ab30bfba697932b2c12b76/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f496e7374616e7449442f496e7374616e7449443f7374796c653d736f6369616c" alt="GitHub" data-canonical-src="https://img.shields.io/github/stars/InstantID/InstantID?style=social" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://huggingface.co/spaces/InstantX/InstantID" rel="nofollow"><img src="https://camo.githubusercontent.com/5762a687b24495afb299c2c0bc68674a2a7dfca9bda6ee444b9da7617d4223a6/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f25463025394625413425393725323048756767696e67253230466163652d5370616365732d626c7565" data-canonical-src="https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue" style="max-width: 100%;"></a>
<a href="https://modelscope.cn/studios/instantx/InstantID/summary" rel="nofollow"><img src="https://camo.githubusercontent.com/5b7cc1acff8b01fae19146a3050daa1a07b968b4369f2db11c37f78416e602ca/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4d6f64656c53636f70652d53747564696f732d626c7565" alt="模型范围" data-canonical-src="https://img.shields.io/badge/ModelScope-Studios-blue" style="max-width: 100%;"></a>
<a href="https://openxlab.org.cn/apps/detail/InstantX/InstantID" rel="nofollow"><img src="https://camo.githubusercontent.com/d78f1ebc38909a3d46852a2fa9925ad7a6f106e5b11bf06450b9af1cdf845cf0/68747470733a2f2f63646e2d7374617469632e6f70656e786c61622e6f72672e636e2f6170702d63656e7465722f6f70656e786c61625f6170702e737667" alt="在 OpenXLab 中打开" data-canonical-src="https://cdn-static.openxlab.org.cn/app-center/openxlab_app.svg" style="max-width: 100%;"></a></p>
</div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">InstantID 是一种新的最先进的免调整方法，只需单个图像即可实现 ID 保留生成，支持各种下游任务。</font></font></p>
<p dir="auto"><a target="_blank" rel="noopener noreferrer" href="/InstantID/InstantID/blob/main/assets/applications.png"><img src="/InstantID/InstantID/raw/main/assets/applications.png" style="max-width: 100%;"></a></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-release" class="anchor" aria-hidden="true" tabindex="-1" href="#release"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发布</font></font></h2>
<ul dir="auto">
<li><font style="vertical-align: inherit;"></font><a href="https://huggingface.co/spaces/InstantX/InstantID" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[2024/02/01] 🔥 我们在Huggingface Spaces 演示</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">中支持了 LCM 加速和 Multi-ControlNets </font><font style="vertical-align: inherit;">！我们的深度估计器由</font></font><a href="https://github.com/LiheYoung/Depth-Anything"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Depth-Anything</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持</font><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[2024/01/31] 🔥 </font></font><a href="https://github.com/siliconflow/onediff?tab=readme-ov-file#easy-to-use"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OneDiff</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在支持 InstantID 加速推理，</font></font><a href="https://github.com/siliconflow/onediff/blob/main/benchmarks/instant_id.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">详情</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请查看！</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[2024/01/23] 🔥 我们的管道已合并为</font></font><a href="https://github.com/huggingface/diffusers/blob/main/examples/community/pipeline_stable_diffusion_xl_instantid.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">扩散器</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">！</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[2024/01/22] 🔥 我们发布了</font></font><a href="https://huggingface.co/InstantX/InstantID" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">预训练的检查点</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://github.com/InstantID/InstantID/blob/main/infer.py"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">推理代码</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://huggingface.co/spaces/InstantX/InstantID" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">渐变演示</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">！</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[2024/01/15] 🔥 我们发布</font></font><a href="https://arxiv.org/abs/2401.07519" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">技术报告</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">[2023/12/11] 🔥 我们启动了</font></font><a href="https://instantid.github.io/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">项目页面</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-demos" class="anchor" aria-hidden="true" tabindex="-1" href="#demos"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">演示</font></font></h2>
<h3 tabindex="-1" dir="auto"><a id="user-content-stylized-synthesis" class="anchor" aria-hidden="true" tabindex="-1" href="#stylized-synthesis"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">程式化合成</font></font></h3>
<p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="/InstantID/InstantID/blob/main/assets/0.png"><img src="/InstantID/InstantID/raw/main/assets/0.png" style="max-width: 100%;"></a>
</p>
<h3 tabindex="-1" dir="auto"><a id="user-content-comparison-with-previous-works" class="anchor" aria-hidden="true" tabindex="-1" href="#comparison-with-previous-works"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与之前作品的比较</font></font></h3>
<p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="/InstantID/InstantID/blob/main/assets/compare-a.png"><img src="/InstantID/InstantID/raw/main/assets/compare-a.png" style="max-width: 100%;"></a>
</p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与现有的免调优最先进技术的比较。 InstantID 实现了更好的保真度并保留了良好的文本可编辑性（面孔和样式更好地融合）。</font></font></p>
<p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="/InstantID/InstantID/blob/main/assets/compare-c.png"><img src="/InstantID/InstantID/raw/main/assets/compare-c.png" style="max-width: 100%;"></a>
</p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与预先训练的角色 LoRA 的比较。我们不需要多个图像，并且无需任何训练仍然可以像 LoRA 一样取得有竞争力的结果。</font></font></p>
<p align="center" dir="auto">
  <a target="_blank" rel="noopener noreferrer" href="/InstantID/InstantID/blob/main/assets/compare-b.png"><img src="/InstantID/InstantID/raw/main/assets/compare-b.png" style="max-width: 100%;"></a>
</p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与 InsightFace Swapper（也称为 ROOP 或 Refactor）的比较。然而，在非写实风格中，我们的作品在面部和背景的融合上更加灵活。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-download" class="anchor" aria-hidden="true" tabindex="-1" href="#download"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://huggingface.co/InstantX/InstantID" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以直接从Huggingface</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载模型</font><font style="vertical-align: inherit;">。您还可以使用 python 脚本下载模型：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">huggingface_hub</span> <span class="pl-k">import</span> <span class="pl-s1">hf_hub_download</span>
<span class="pl-en">hf_hub_download</span>(<span class="pl-s1">repo_id</span><span class="pl-c1">=</span><span class="pl-s">"InstantX/InstantID"</span>, <span class="pl-s1">filename</span><span class="pl-c1">=</span><span class="pl-s">"ControlNetModel/config.json"</span>, <span class="pl-s1">local_dir</span><span class="pl-c1">=</span><span class="pl-s">"./checkpoints"</span>)
<span class="pl-en">hf_hub_download</span>(<span class="pl-s1">repo_id</span><span class="pl-c1">=</span><span class="pl-s">"InstantX/InstantID"</span>, <span class="pl-s1">filename</span><span class="pl-c1">=</span><span class="pl-s">"ControlNetModel/diffusion_pytorch_model.safetensors"</span>, <span class="pl-s1">local_dir</span><span class="pl-c1">=</span><span class="pl-s">"./checkpoints"</span>)
<span class="pl-en">hf_hub_download</span>(<span class="pl-s1">repo_id</span><span class="pl-c1">=</span><span class="pl-s">"InstantX/InstantID"</span>, <span class="pl-s1">filename</span><span class="pl-c1">=</span><span class="pl-s">"ip-adapter.bin"</span>, <span class="pl-s1">local_dir</span><span class="pl-c1">=</span><span class="pl-s">"./checkpoints"</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="from huggingface_hub import hf_hub_download
hf_hub_download(repo_id=&quot;InstantX/InstantID&quot;, filename=&quot;ControlNetModel/config.json&quot;, local_dir=&quot;./checkpoints&quot;)
hf_hub_download(repo_id=&quot;InstantX/InstantID&quot;, filename=&quot;ControlNetModel/diffusion_pytorch_model.safetensors&quot;, local_dir=&quot;./checkpoints&quot;)
hf_hub_download(repo_id=&quot;InstantX/InstantID&quot;, filename=&quot;ip-adapter.bin&quot;, local_dir=&quot;./checkpoints&quot;)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或者运行以下命令下载所有模型：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">pip</span> <span class="pl-s1">install</span> <span class="pl-c1">-</span><span class="pl-s1">r</span> <span class="pl-s1">gradio_demo</span><span class="pl-c1">/</span><span class="pl-s1">requirements</span>.<span class="pl-s1">txt</span>
<span class="pl-s1">python</span> <span class="pl-s1">gradio_demo</span><span class="pl-c1">/</span><span class="pl-s1">download_models</span>.<span class="pl-s1">py</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pip install -r gradio_demo/requirements.txt
python gradio_demo/download_models.py" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果无法访问Huggingface，可以使用</font></font><a href="https://hf-mirror.com/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">hf-mirror</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下载模型。</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">export</span> <span class="pl-v">HF_ENDPOINT</span><span class="pl-c1">=</span><span class="pl-s1">https</span>:<span class="pl-c1">//</span><span class="pl-s1">hf</span><span class="pl-c1">-</span><span class="pl-s1">mirror</span>.<span class="pl-s1">com</span>
<span class="pl-s1">huggingface</span><span class="pl-c1">-</span><span class="pl-s1">cli</span> <span class="pl-s1">download</span> <span class="pl-c1">-</span><span class="pl-c1">-</span><span class="pl-s1">resume</span><span class="pl-c1">-</span><span class="pl-s1">download</span> <span class="pl-v">InstantX</span><span class="pl-c1">/</span><span class="pl-v">InstantID</span> <span class="pl-c1">-</span><span class="pl-c1">-</span><span class="pl-s1">local</span><span class="pl-c1">-</span><span class="pl-s1">dir</span> <span class="pl-s1">checkpoints</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="export HF_ENDPOINT=https://hf-mirror.com
huggingface-cli download --resume-download InstantX/InstantID --local-dir checkpoints" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于人脸编码器，您需要通过此</font></font><a href="https://github.com/deepinsight/insightface/issues/1896#issuecomment-1023867304" data-hovercard-type="issue" data-hovercard-url="/deepinsight/insightface/issues/1896/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">URL</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">手动下载，因为</font></font><code>models/antelopev2</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">默认链接无效。准备好所有模型后，文件夹树应如下所示：</font></font></p>
<div class="snippet-clipboard-content notranslate position-relative overflow-auto"><pre class="notranslate"><code>  .
  ├── models
  ├── checkpoints
  ├── ip_adapter
  ├── pipeline_stable_diffusion_xl_instantid.py
  └── README.md
</code></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="  .
  ├── models
  ├── checkpoints
  ├── ip_adapter
  ├── pipeline_stable_diffusion_xl_instantid.py
  └── README.md" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-usage" class="anchor" aria-hidden="true" tabindex="-1" href="#usage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用法</font></font></h2>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"># !pip install opencv-python transformers accelerate insightface</span>
<span class="pl-k">import</span> <span class="pl-s1">diffusers</span>
<span class="pl-k">from</span> <span class="pl-s1">diffusers</span>.<span class="pl-s1">utils</span> <span class="pl-k">import</span> <span class="pl-s1">load_image</span>
<span class="pl-k">from</span> <span class="pl-s1">diffusers</span>.<span class="pl-s1">models</span> <span class="pl-k">import</span> <span class="pl-v">ControlNetModel</span>

<span class="pl-k">import</span> <span class="pl-s1">cv2</span>
<span class="pl-k">import</span> <span class="pl-s1">torch</span>
<span class="pl-k">import</span> <span class="pl-s1">numpy</span> <span class="pl-k">as</span> <span class="pl-s1">np</span>
<span class="pl-k">from</span> <span class="pl-v">PIL</span> <span class="pl-k">import</span> <span class="pl-v">Image</span>

<span class="pl-k">from</span> <span class="pl-s1">insightface</span>.<span class="pl-s1">app</span> <span class="pl-k">import</span> <span class="pl-v">FaceAnalysis</span>
<span class="pl-k">from</span> <span class="pl-s1">pipeline_stable_diffusion_xl_instantid</span> <span class="pl-k">import</span> <span class="pl-v">StableDiffusionXLInstantIDPipeline</span>, <span class="pl-s1">draw_kps</span>

<span class="pl-c"># prepare 'antelopev2' under ./models</span>
<span class="pl-s1">app</span> <span class="pl-c1">=</span> <span class="pl-v">FaceAnalysis</span>(<span class="pl-s1">name</span><span class="pl-c1">=</span><span class="pl-s">'antelopev2'</span>, <span class="pl-s1">root</span><span class="pl-c1">=</span><span class="pl-s">'./'</span>, <span class="pl-s1">providers</span><span class="pl-c1">=</span>[<span class="pl-s">'CUDAExecutionProvider'</span>, <span class="pl-s">'CPUExecutionProvider'</span>])
<span class="pl-s1">app</span>.<span class="pl-en">prepare</span>(<span class="pl-s1">ctx_id</span><span class="pl-c1">=</span><span class="pl-c1">0</span>, <span class="pl-s1">det_size</span><span class="pl-c1">=</span>(<span class="pl-c1">640</span>, <span class="pl-c1">640</span>))

<span class="pl-c"># prepare models under ./checkpoints</span>
<span class="pl-s1">face_adapter</span> <span class="pl-c1">=</span> <span class="pl-s">f'./checkpoints/ip-adapter.bin'</span>
<span class="pl-s1">controlnet_path</span> <span class="pl-c1">=</span> <span class="pl-s">f'./checkpoints/ControlNetModel'</span>

<span class="pl-c"># load IdentityNet</span>
<span class="pl-s1">controlnet</span> <span class="pl-c1">=</span> <span class="pl-v">ControlNetModel</span>.<span class="pl-en">from_pretrained</span>(<span class="pl-s1">controlnet_path</span>, <span class="pl-s1">torch_dtype</span><span class="pl-c1">=</span><span class="pl-s1">torch</span>.<span class="pl-s1">float16</span>)

<span class="pl-s1">base_model</span> <span class="pl-c1">=</span> <span class="pl-s">'wangqixun/YamerMIX_v8'</span>  <span class="pl-c"># from https://civitai.com/models/84040?modelVersionId=196039</span>
<span class="pl-s1">pipe</span> <span class="pl-c1">=</span> <span class="pl-v">StableDiffusionXLInstantIDPipeline</span>.<span class="pl-en">from_pretrained</span>(
    <span class="pl-s1">base_model</span>,
    <span class="pl-s1">controlnet</span><span class="pl-c1">=</span><span class="pl-s1">controlnet</span>,
    <span class="pl-s1">torch_dtype</span><span class="pl-c1">=</span><span class="pl-s1">torch</span>.<span class="pl-s1">float16</span>
)
<span class="pl-s1">pipe</span>.<span class="pl-en">cuda</span>()

<span class="pl-c"># load adapter</span>
<span class="pl-s1">pipe</span>.<span class="pl-en">load_ip_adapter_instantid</span>(<span class="pl-s1">face_adapter</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# !pip install opencv-python transformers accelerate insightface
import diffusers
from diffusers.utils import load_image
from diffusers.models import ControlNetModel

import cv2
import torch
import numpy as np
from PIL import Image

from insightface.app import FaceAnalysis
from pipeline_stable_diffusion_xl_instantid import StableDiffusionXLInstantIDPipeline, draw_kps

# prepare 'antelopev2' under ./models
app = FaceAnalysis(name='antelopev2', root='./', providers=['CUDAExecutionProvider', 'CPUExecutionProvider'])
app.prepare(ctx_id=0, det_size=(640, 640))

# prepare models under ./checkpoints
face_adapter = f'./checkpoints/ip-adapter.bin'
controlnet_path = f'./checkpoints/ControlNetModel'

# load IdentityNet
controlnet = ControlNetModel.from_pretrained(controlnet_path, torch_dtype=torch.float16)

base_model = 'wangqixun/YamerMIX_v8'  # from https://civitai.com/models/84040?modelVersionId=196039
pipe = StableDiffusionXLInstantIDPipeline.from_pretrained(
    base_model,
    controlnet=controlnet,
    torch_dtype=torch.float16
)
pipe.cuda()

# load adapter
pipe.load_ip_adapter_instantid(face_adapter)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然后，您可以定制自己的脸部图像</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"># load an image</span>
<span class="pl-s1">face_image</span> <span class="pl-c1">=</span> <span class="pl-en">load_image</span>(<span class="pl-s">"./examples/yann-lecun_resize.jpg"</span>)

<span class="pl-c"># prepare face emb</span>
<span class="pl-s1">face_info</span> <span class="pl-c1">=</span> <span class="pl-s1">app</span>.<span class="pl-en">get</span>(<span class="pl-s1">cv2</span>.<span class="pl-en">cvtColor</span>(<span class="pl-s1">np</span>.<span class="pl-en">array</span>(<span class="pl-s1">face_image</span>), <span class="pl-s1">cv2</span>.<span class="pl-v">COLOR_RGB2BGR</span>))
<span class="pl-s1">face_info</span> <span class="pl-c1">=</span> <span class="pl-en">sorted</span>(<span class="pl-s1">face_info</span>, <span class="pl-s1">key</span><span class="pl-c1">=</span><span class="pl-k">lambda</span> <span class="pl-s1">x</span>:(<span class="pl-s1">x</span>[<span class="pl-s">'bbox'</span>][<span class="pl-c1">2</span>]<span class="pl-c1">-</span><span class="pl-s1">x</span>[<span class="pl-s">'bbox'</span>][<span class="pl-c1">0</span>])<span class="pl-c1">*</span><span class="pl-s1">x</span>[<span class="pl-s">'bbox'</span>][<span class="pl-c1">3</span>]<span class="pl-c1">-</span><span class="pl-s1">x</span>[<span class="pl-s">'bbox'</span>][<span class="pl-c1">1</span>])[<span class="pl-c1">-</span><span class="pl-c1">1</span>]  <span class="pl-c"># only use the maximum face</span>
<span class="pl-s1">face_emb</span> <span class="pl-c1">=</span> <span class="pl-s1">face_info</span>[<span class="pl-s">'embedding'</span>]
<span class="pl-s1">face_kps</span> <span class="pl-c1">=</span> <span class="pl-en">draw_kps</span>(<span class="pl-s1">face_image</span>, <span class="pl-s1">face_info</span>[<span class="pl-s">'kps'</span>])

<span class="pl-c"># prompt</span>
<span class="pl-s1">prompt</span> <span class="pl-c1">=</span> <span class="pl-s">"film noir style, ink sketch|vector, male man, highly detailed, sharp focus, ultra sharpness, monochrome, high contrast, dramatic shadows, 1940s style, mysterious, cinematic"</span>
<span class="pl-s1">negative_prompt</span> <span class="pl-c1">=</span> <span class="pl-s">"ugly, deformed, noisy, blurry, low contrast, realism, photorealistic, vibrant, colorful"</span>

<span class="pl-c"># generate image</span>
<span class="pl-s1">image</span> <span class="pl-c1">=</span> <span class="pl-en">pipe</span>(
    <span class="pl-s1">prompt</span>,
    <span class="pl-s1">image_embeds</span><span class="pl-c1">=</span><span class="pl-s1">face_emb</span>,
    <span class="pl-s1">image</span><span class="pl-c1">=</span><span class="pl-s1">face_kps</span>,
    <span class="pl-s1">controlnet_conditioning_scale</span><span class="pl-c1">=</span><span class="pl-c1">0.8</span>,
    <span class="pl-s1">ip_adapter_scale</span><span class="pl-c1">=</span><span class="pl-c1">0.8</span>,
).<span class="pl-s1">images</span>[<span class="pl-c1">0</span>]</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# load an image
face_image = load_image(&quot;./examples/yann-lecun_resize.jpg&quot;)

# prepare face emb
face_info = app.get(cv2.cvtColor(np.array(face_image), cv2.COLOR_RGB2BGR))
face_info = sorted(face_info, key=lambda x:(x['bbox'][2]-x['bbox'][0])*x['bbox'][3]-x['bbox'][1])[-1]  # only use the maximum face
face_emb = face_info['embedding']
face_kps = draw_kps(face_image, face_info['kps'])

# prompt
prompt = &quot;film noir style, ink sketch|vector, male man, highly detailed, sharp focus, ultra sharpness, monochrome, high contrast, dramatic shadows, 1940s style, mysterious, cinematic&quot;
negative_prompt = &quot;ugly, deformed, noisy, blurry, low contrast, realism, photorealistic, vibrant, colorful&quot;

# generate image
image = pipe(
    prompt,
    image_embeds=face_emb,
    image=face_kps,
    controlnet_conditioning_scale=0.8,
    ip_adapter_scale=0.8,
).images[0]" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了节省 VRAM，您可以启用 CPU 卸载</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">pipe</span>.<span class="pl-en">enable_model_cpu_offload</span>()</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="pipe.enable_model_cpu_offload()" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-speed-up-with-lcm-lora" class="anchor" aria-hidden="true" tabindex="-1" href="#speed-up-with-lcm-lora"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用 LCM-LoRA 加速</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://github.com/luosiallen/latent-consistency-model"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的工作与LCM-LoRA</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">兼容</font><font style="vertical-align: inherit;">。首先，下载模型。</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">huggingface_hub</span> <span class="pl-k">import</span> <span class="pl-s1">hf_hub_download</span>
<span class="pl-en">hf_hub_download</span>(<span class="pl-s1">repo_id</span><span class="pl-c1">=</span><span class="pl-s">"latent-consistency/lcm-lora-sdxl"</span>, <span class="pl-s1">filename</span><span class="pl-c1">=</span><span class="pl-s">"pytorch_lora_weights.safetensors"</span>, <span class="pl-s1">local_dir</span><span class="pl-c1">=</span><span class="pl-s">"./checkpoints"</span>)</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="from huggingface_hub import hf_hub_download
hf_hub_download(repo_id=&quot;latent-consistency/lcm-lora-sdxl&quot;, filename=&quot;pytorch_lora_weights.safetensors&quot;, local_dir=&quot;./checkpoints&quot;)" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要使用它，您只需加载它并用一个小的 num_inference_steps 进行推断。注意，建议将guiding_scale设置在[0, 1]之间。</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">from</span> <span class="pl-s1">diffusers</span> <span class="pl-k">import</span> <span class="pl-v">LCMScheduler</span>

<span class="pl-s1">lcm_lora_path</span> <span class="pl-c1">=</span> <span class="pl-s">"./checkpoints/pytorch_lora_weights.safetensors"</span>

<span class="pl-s1">pipe</span>.<span class="pl-en">load_lora_weights</span>(<span class="pl-s1">lcm_lora_path</span>)
<span class="pl-s1">pipe</span>.<span class="pl-en">fuse_lora</span>()
<span class="pl-s1">pipe</span>.<span class="pl-s1">scheduler</span> <span class="pl-c1">=</span> <span class="pl-v">LCMScheduler</span>.<span class="pl-en">from_config</span>(<span class="pl-s1">pipe</span>.<span class="pl-s1">scheduler</span>.<span class="pl-s1">config</span>)

<span class="pl-s1">num_inference_steps</span> <span class="pl-c1">=</span> <span class="pl-c1">10</span>
<span class="pl-s1">guidance_scale</span> <span class="pl-c1">=</span> <span class="pl-c1">0</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="from diffusers import LCMScheduler

lcm_lora_path = &quot;./checkpoints/pytorch_lora_weights.safetensors&quot;

pipe.load_lora_weights(lcm_lora_path)
pipe.fuse_lora()
pipe.scheduler = LCMScheduler.from_config(pipe.scheduler.config)

num_inference_steps = 10
guidance_scale = 0" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-start-a-local-gradio-demo-" class="anchor" aria-hidden="true" tabindex="-1" href="#start-a-local-gradio-demo-"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启动本地渐变演示</font></font><a href="https://github.com/gradio-app/gradio"><img src="https://camo.githubusercontent.com/f8b88bb760ab03bce3155f04a55d4b0b3fc3e4a5b982fcb0fc97283c0ac94fde/68747470733a2f2f696d672e736869656c64732e696f2f6769746875622f73746172732f67726164696f2d6170702f67726164696f" data-canonical-src="https://img.shields.io/github/stars/gradio-app/gradio" style="max-width: 100%;"></a></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">运行以下命令：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">python</span> <span class="pl-s1">gradio_demo</span><span class="pl-c1">/</span><span class="pl-s1">app</span>.<span class="pl-s1">py</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="python gradio_demo/app.py" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或 MultiControlNet 版本：</font></font></p>
<div class="highlight highlight-source-python notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-s1">gradio_demo</span><span class="pl-c1">/</span><span class="pl-s1">app</span><span class="pl-c1">-</span><span class="pl-s1">multicontrolnet</span>.<span class="pl-s1">py</span> </pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="gradio_demo/app-multicontrolnet.py " tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<h2 tabindex="-1" dir="auto"><a id="user-content-usage-tips" class="anchor" aria-hidden="true" tabindex="-1" href="#usage-tips"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用技巧</font></font></h2>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了获得更高的相似度，请增加controlnet_conditioning_scale（IdentityNet）和ip_adapter_scale（Adapter）的权重。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于过饱和，请减小 ip_adapter_scale。如果不起作用，请减少 controlnet_conditioning_scale。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为了获得更高的文本控制能力，请减小 ip_adapter_scale。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">针对具体款式，选择相应的底座型号会有差异。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们还不支持多人，仅使用最大的人脸作为参考面部标志。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们提供</font></font><a href="https://github.com/ahgsql/StyleSelectorXL/blob/main/sdxl_styles.json"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">样式模板</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">供参考。</font></font></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-community-resources" class="anchor" aria-hidden="true" tabindex="-1" href="#community-resources"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">社区资源</font></font></h2>
<h3 tabindex="-1" dir="auto"><a id="user-content-replicate-demo" class="anchor" aria-hidden="true" tabindex="-1" href="#replicate-demo"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">复制演示</font></font></h3>
<ul dir="auto">
<li><a href="https://replicate.com/zsxkib/instant-id" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">zsxkib/即时 ID</font></font></a></li>
</ul>
<h3 tabindex="-1" dir="auto"><a id="user-content-webui" class="anchor" aria-hidden="true" tabindex="-1" href="#webui"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">网页界面</font></font></h3>
<ul dir="auto">
<li><a href="https://github.com/Mikubill/sd-webui-controlnet/discussions/2589" data-hovercard-type="discussion" data-hovercard-url="/Mikubill/sd-webui-controlnet/discussions/2589/hovercard"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Mikubil/sd-webui-controlnet</font></font></a></li>
</ul>
<h3 tabindex="-1" dir="auto"><a id="user-content-comfyui" class="anchor" aria-hidden="true" tabindex="-1" href="#comfyui"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">舒适用户界面</font></font></h3>
<ul dir="auto">
<li><a href="https://github.com/ZHO-ZHO-ZHO/ComfyUI-InstantID"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ZHO-ZHO-ZHO/ComfyUI-InstantID</font></font></a></li>
<li><a href="https://github.com/huxiuhan/ComfyUI-InstantID"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">huxiuhan/ComfyUI-InstantID</font></font></a></li>
</ul>
<h3 tabindex="-1" dir="auto"><a id="user-content-windows" class="anchor" aria-hidden="true" tabindex="-1" href="#windows"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">视窗</font></font></h3>
<ul dir="auto">
<li><a href="https://github.com/sdbds/InstantID-for-windows"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">sdbds/Windows 的 InstantID</font></font></a></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-acknowledgements" class="anchor" aria-hidden="true" tabindex="-1" href="#acknowledgements"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">致谢</font></font></h2>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">InstantID由小红书InstantX团队开发，保留所有版权。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">我们的工作深受</font></font><a href="https://github.com/tencent-ailab/IP-Adapter"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IP-Adapter</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><a href="https://github.com/lllyasviel/ControlNet"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ControlNet</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的启发。感谢他们的精彩作品！</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">感谢</font></font><a href="https://civitai.com/user/Yamer" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Yamer</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开发</font></font><a href="https://civitai.com/models/84040?modelVersionId=196039" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">YamerMIX</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">，我们在演示中使用它作为基础模型。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">感谢</font></font><a href="https://github.com/ZHO-ZHO-ZHO"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ZHO-ZHO-ZHO</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://github.com/huxiuhan"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">huxiuhan</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://github.com/sdbds"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">sdbds</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><a href="https://replicate.com/zsxkib" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">zsxkib</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的慷慨贡献。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">感谢</font></font><a href="https://github.com/huggingface"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">HuggingFace</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> gradio 团队提供的免费 G&ZeroWidthSpace;&ZeroWidthSpace;PU 支持！</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">感谢</font></font><a href="https://github.com/modelscope/modelscope"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">ModelScope</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">团队提供的免费 G&ZeroWidthSpace;&ZeroWidthSpace;PU 支持！</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">感谢</font></font><a href="https://openxlab.org.cn/apps/detail/InstantX/InstantID" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenXLab</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">团队提供的免费 G&ZeroWidthSpace;&ZeroWidthSpace;PU 支持！</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">感谢</font></font><a href="https://github.com/siliconflow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">SiliconFlow</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对 InstantID 的 OneDiff 集成！</font></font></li>
</ul>
<h2 tabindex="-1" dir="auto"><a id="user-content-disclaimer" class="anchor" aria-hidden="true" tabindex="-1" href="#disclaimer"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">免责声明</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://github.com/InstantID/InstantID?tab=Apache-2.0-1-ov-file#readme"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">InstantID 的代码在Apache 许可证</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">下发布，</font><font style="vertical-align: inherit;">可供学术和商业用途。</font></font><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">然而，从insightface手动下载和自动下载人脸模型仅根据</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">其</font></font><a href="https://github.com/deepinsight/insightface?tab=readme-ov-file#license"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">许可</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用于非商业研究目的。用户可以自由地使用此工具创建图像，但他们有义务遵守当地法律并负责任地使用它。开发者对用户潜在的误用不承担任何责任。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-star-history" class="anchor" aria-hidden="true" tabindex="-1" href="#star-history"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">明星历史</font></font></h2>
<p dir="auto"><a href="https://star-history.com/#InstantID/InstantID&amp;Date" rel="nofollow"><img src="https://camo.githubusercontent.com/bb28fdc48595f259af7a12e7fdc496676170f559b8a113e77b9d518e230d5a2f/68747470733a2f2f6170692e737461722d686973746f72792e636f6d2f7376673f7265706f733d496e7374616e7449442f496e7374616e74494426747970653d44617465" alt="明星历史图" data-canonical-src="https://api.star-history.com/svg?repos=InstantID/InstantID&amp;type=Date" style="max-width: 100%;"></a></p>
<h2 tabindex="-1" dir="auto"><a id="user-content-cite" class="anchor" aria-hidden="true" tabindex="-1" href="#cite"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">引用</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您发现 InstantID 对您的研究和应用有用，请使用此 BibTeX 引用我们：</font></font></p>
<div class="highlight highlight-text-bibtex notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-k">@article</span>{<span class="pl-en">wang2024instantid</span>,
  <span class="pl-s">title</span>=<span class="pl-s"><span class="pl-pds">{</span>InstantID: Zero-shot Identity-Preserving Generation in Seconds<span class="pl-pds">}</span></span>,
  <span class="pl-s">author</span>=<span class="pl-s"><span class="pl-pds">{</span>Wang, Qixun and Bai, Xu and Wang, Haofan and Qin, Zekui and Chen, Anthony<span class="pl-pds">}</span></span>,
  <span class="pl-s">journal</span>=<span class="pl-s"><span class="pl-pds">{</span>arXiv preprint arXiv:2401.07519<span class="pl-pds">}</span></span>,
  <span class="pl-s">year</span>=<span class="pl-s"><span class="pl-pds">{</span>2024<span class="pl-pds">}</span></span>
}</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="@article{wang2024instantid,
  title={InstantID: Zero-shot Identity-Preserving Generation in Seconds},
  author={Wang, Qixun and Bai, Xu and Wang, Haofan and Qin, Zekui and Chen, Anthony},
  journal={arXiv preprint arXiv:2401.07519},
  year={2024}
}" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如有任何疑问，请随时通过</font></font><a href="mailto:haofanwang.ai@gmail.com"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">haofanwang.ai@gmail.com</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><a href="mailto:wangqixun.ai@gmail.com"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">wangqixun.ai@gmail.com</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">与我们联系。</font></font></p>
</article></div>
