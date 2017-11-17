# Replication Package for "The Impact of Code Review Coverage and Code Review Participation on Software Quality: A Case Study of the Qt, VTK, and ITK Projects"

Shane McIntosh, Yasutaka Kamei, Bram Adams, and Ahmed E. Hassan  
[In Proceedings of the 11th Working Conference on Mining Software Repositories - MSR 2014](http://doi.acm.org/10.1145/2597073.2597076)

Abstract. Software code review, i.e., the practice of having third-party team members critique changes to a software system, is a well-established best practice in both open source and proprietary software domains. Prior work has shown that the formal code inspections of the past tend to improve the quality of software delivered by students and small teams. However, the formal code inspection process mandates strict review criteria (e.g., in-person meetings and reviewer checklists) to ensure a base level of review quality, while the modern, lightweight code reviewing process does not. Although recent work explores the modern code review from a qualitative perspective, little research quantitatively explores the relationship between properties of the modern code review process and software quality. Hence, in this paper, we study the relationship between software quality and: (1) code review coverage, i.e., the proportion of changes that have been code reviewed, and (2) code review participation, i.e., the degree of reviewer involvement in the code review process. Through a case study of the Qt, VTK, and ITK projects, we find that both review coverage and participation share a significant link with software quality. Low review coverage and participation are estimated to produce components with up to two and five additional post-release defects respectively. Our results empirically confirm the intuition that poorly reviewed code has a negative impact on software quality in large systems using modern reviewing tools. 

## Bibtex

```bibtex
@inproceedings{McIntosh:2014:ICR:2597073.2597076,
 author = {McIntosh, Shane and Kamei, Yasutaka and Adams, Bram and Hassan, Ahmed E.},
 title = {The Impact of Code Review Coverage and Code Review Participation on Software Quality: A Case Study of the Qt, VTK, and ITK Projects},
 booktitle = {Proceedings of the 11th Working Conference on Mining Software Repositories},
 series = {MSR 2014},
 year = {2014},
 isbn = {978-1-4503-2863-0},
 location = {Hyderabad, India},
 pages = {192--201},
 numpages = {10},
 url = {http://doi.acm.org/10.1145/2597073.2597076},
 doi = {10.1145/2597073.2597076},
 acmid = {2597076},
 publisher = {ACM},
 address = {New York, NY, USA},
 keywords = {Code reviews, software quality},
} 
```
## Data

[VCS commit and gerrit code review data (MySQL dump, 45 MB)](https://github.com/SAILResearch/replication-code_review_sw_quality/releases/latest)
