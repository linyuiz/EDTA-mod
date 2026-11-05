# EDTA-mod -- This is a modified version of EDTA
For those working on genome transposon annotation, EDTA (Extensive de novo TE Annotator) is a familiar name. It is currently recognized as one of the most accurate annotation pipelines, but the original workflow often presents several frustrating issues during execution:  

**1️⃣Efficiency bottleneck**: Serial execution leads to low CPU utilization, such as in the initial rawTE search phase.  

**2️⃣Catastrophic crashes**: After running for days, it may suddenly throw an error with no solution, even though some errors can be ignored without affecting the results.  

**3️⃣Black-box operations**: A tangled mix of lengthy Shell and Perl commands makes parameter adjustments cumbersome and the code difficult to read.  

To address these problems, we recently undertook a complete overhaul of EDTA—introducing the Nextflow workflow engine alongside Shell scripts, breathing new life into this well-established software.

⭐️If you encounter any issues, feel free to ask in the issue section. Please also support the original authors. **If you use EDTA, kindly cite it:**   

Ou S., Su W., Liao Y., Chougule K., Agda J. R. A., Hellinga A. J., Lugo C. S. B., Elliott T. A., Ware D., Peterson T., Jiang N.✉, Hirsch C. N.✉ and Hufford M. B.✉ (2019). Benchmarking Transposable Element Annotation Methods for Creation of a Streamlined, Comprehensive Pipeline. Genome Biol. 20(1): 275. 

---

# Other modified versions of the software
⭐️ [**CPhasing-mod**](https://github.com/linyuiz/CPhasing-mod): Revised version of the genome scaffolding software [**C-Phasing**](https://wangyibin.github.io/CPhasing/).

⭐️ [**EDTA-mod**](https://github.com/linyuiz/EDTA-mod): Revised version of the TE annotation software [**EDTA**](https://github.com/oushujun/EDTA).

⭐️ [**GINGER-mod**](https://github.com/linyuiz/GINGER-mod): Revised version of the genome annotation software [**GINGER**](https://github.com/i10labtitech/GINGER).

---

# Installation
<p align="center"><strong>[ <a href="https://github.com/linyuiz/zgtools/wiki/English">English Wiki</a> | <a href="https://github.com/linyuiz/zgtools/wiki/%E7%AE%80%E4%BD%93%E4%B8%AD%E6%96%87">中文维基</a> ]</strong></p>
