# Global aboveground biomass estimate

This research code upscales sparse aboveground biomass (AGB) footprints into a 30-meter resolution global estimate for summertime 2021. We use an ensemble of machine learning models, including random forest (RF) and XGBoost and combine both radar and optical hyperspectral imagery from Sentinel-1 and Sentinel-2, respectively. We further constrain our ensemble with the physical parameter of gross primary production (GPP), estimated on a global scale by solar-induced fluorescence (SIF). We find that our ML ensemble reduces validation error by ~10%, and the addition of SIF-based GPP further reduces it by ~7% showing the importance of using a variable with physical-meaning to guide how ML models learn.

## Related works
This work is still under review. But you can check out similar works below:
1. AGB estimate using deep network
```
@article{nathaniel2022aboveground,
	title={Aboveground carbon biomass estimate with Physics-informed deep network},
	author={Nathaniel, Juan and Klein, Levente J and Watson, Campbell D and Nyirjesy, Gabrielle and Albrecht, Conrad M},
	journal={arXiv preprint arXiv:2210.13752},
	year={2022}
}
```

2. AI platform for biomass multimodal estimates 
```
@inproceedings{da2022netzeroco,
	title={NetZeroCO 2, an AI framework for accelerated nature-based carbon sequestration},
	author={da Silva, Ademir Ferreira and Nathaniel, Juan and Wong, Ken CL and Watson, Campbell and Wang, Hongzhi and Singh, Jitendra and Chamon, Alexandre Alkmim and Klein, Levente},
	booktitle={2022 IEEE International Conference on Big Data (Big Data)},
	pages={4881--4887},
	year={2022},
	organization={IEEE}
}
```
