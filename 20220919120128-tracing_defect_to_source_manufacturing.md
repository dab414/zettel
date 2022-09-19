# 20220919120128-tracing_defect_to_source_manufacturing

#hcps #defect #tracing #detection #develop #domain

One of the most harmful outcomes of an attack can be the impact that the attack has on
other networks (see [[20220919100750-forward_feeding_attack.md]]; sreeramagiri et al.,
2022). One reason for this is because if a defect is detected in a product (see
[[20220919115705-detecting_cyber_attacks_manufacturing.md]]), it becomes difficult to
trace the defect back to its source. 

For studies exploring challenges associated with defect detection and source tracing see
[1-3]. 

Two challenges associated with tracing to source (Ganesh):

* Identifying the faulty component and where it came from.
    * This is challenging but doable in principle. If I can identify that a product failed
        because of a bad screw, I can potentially identify where that screw came from.
* Identifying the source of the fault.
    * Difficult if not impossible to determine whether the fault stemmed from humans /
        non-humans or malicious intent vs. negligence.
    * Especially since machines have stochastic error---they'll fail some small percentage
        of the time even in the best conditions.

**References**

sreeramagiri et al., 2002; no bibtex available; https://doi.org/10.1520/SSMS20210042 

conversation with ganesh (2022-09-19)

1. @article{wells2014cyber,
  title={Cyber-physical security challenges in manufacturing systems},
  author={Wells, Lee J and Camelio, Jaime A and Williams, Christopher B and White, Jules},
  journal={Manufacturing Letters},
  volume={2},
  number={2},
  pages={74--77},
  year={2014},
  publisher={Elsevier}
}

2. @inproceedings{sturm2014cyber,
  title={Cyber-physical vulnerabilities in additive manufacturing systems},
  author={Sturm, Logan D and Williams, Christopher B and Camelio, Jamie A and White, Jules and Parker, Robert},
  booktitle={2014 International Solid Freeform Fabrication Symposium},
  year={2014},
  organization={University of Texas at Austin}
}

3. @article{elhabashy2019cyber,
  title={Cyber-physical security research efforts in manufacturing--a literature review},
  author={Elhabashy, Ahmad E and Wells, Lee J and Camelio, Jaime A},
  journal={Procedia manufacturing},
  volume={34},
  pages={921--931},
  year={2019},
  publisher={Elsevier}
}

