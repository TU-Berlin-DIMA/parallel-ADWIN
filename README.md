
# Scalable Detection of Concept Drifts on Data Streams with Parallel Adaptive Windowing
This repository contains a description and source code for Scalable Detection of Concept Drifts on Data Streams with Parallel Adaptive Windowing

## Parallel Adwin at EDBT 2017
Parallel Adwin was first published at the 21th International Conference on Extending Database Technology (EDBT) in March 2018.  

**Abstract:** Machine Learning (ML) techniques for data stream analysis suffer from concept drifts such as changed user preferences, varying weather conditions, or economic changes. These concept drifts
cause wrong predictions and lead to incorrect business decisions. Concept drift detection methods such as adaptive windowing (Adwin) allow for adapting to concept drifts on the fly. In this paper, we examine Adwin in detail and point out its throughput bottlenecks. We then introduce several parallelization alternatives to address these bottlenecks. Our optimizations increase the throughput of the original Adwin approach by two orders of magnitude. Thus, we explore parallel adaptive windowing to provide scalable concept detection for high-velocity data streams with millions of tuples per second.

**Publication:**
- Paper: [Scalable Detection of Concept Drifts on Data Streams
with Parallel Adaptive Windowing](http://www.redaktion.tu-berlin.de/fileadmin/fg131/Publikation/Papers/preprint_adwin-paper-EDBT18_wm.pdf)

- BibTeX citation:
```
@inproceedings{traub2017i2,
  title={Scalable Detection of Concept Drifts on Data Streams with Parallel Adaptive Windowing},
  author={Grulich, Philipp Marian and Saitenmacher, René and Traub, Jonas and Breß, Sebastian and Rabl, Tilmann and Markl, Volker},
  booktitle={21th International Conference on Extending Database Technology (EDBT)},
  pages={???},
  year={2018}
}
```