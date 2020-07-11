# About this project
SARS-CoV-2, more commonly referred to as COVID-19 or as 'the coronavirus', has quickly become a dangerous diesease partly due to its ability to spread asymptomatically. However, the responses of countries like Iceland, Germany, and South Korea have demonstrated that comprehensive and readily available testing is an effective strategy at identifying and reducing transmission spread.

As various parts of the world seek to re-open, and as others are still facing a rising number of cases, the need for quick, low-cost, and high-speed testing has become apparent. An increasing number of studies have demonstrated that oxygen levels in Covid-19 patients are measureably lower than in healthy individuals. The Sentinel project seeks to use this observation to create a low-cost, easy-to-manufacture device which can be deployed in schools, workplaces, care facilities, and other population-dense areas to provide an advanced warning for asymptomatic carriers. Given the speed at which oximeters measure and provide results, individuals can be tested on the spot and be permitted or denied entry based on the result.

# Technical Overview
Components are aimed at being low-cost and hobbyist accesible. The 'brain' of the device is a Raspberry Pi 3B+, which interfaces into a Maxim Integrated 3010 oximeter to measure oxygen levels. This information is then reported to the end user in an attempt to provide actionable data.

## Getting Started
See the repositories associated with this project. More information coming soon.

## Peer-Reviewed Further Reading
Highly-cited paper describing Covid-19 symptoms, in which oxygen therapy was adminstered to 41.3% of patients, indicating they had low oxygen levels:
- Guan WJ, Ni ZY, Hu Y, Liang WH, Ou CQ, He JX, Liu L, Shan H, Lei CL, Hui DSC, Du B, Li LJ, Zeng G, Yuen KY, Chen RC, Tang CL, Wang T, Chen PY, Xiang J, Li SY, Wang JL, Liang ZJ, Peng YX, Wei L, Liu Y, Hu YH, Peng P, Wang JM, Liu JY, Chen Z, Li G, Zheng ZJ, Qiu SQ, Luo J, Ye CJ, Zhu SY, Zhong NS, China Medical Treatment Expert Group for C Clinical characteristics of Coronavirus Disease 2019 in China. N Engl J Med. 2020 

Paper describing links between hypoxia and mortality in Covid patients:
- Jiang Xie MD, PhD, Naima Covassin PhD, Zhengyang Fan MD, Prachi Singh PhD, Wei Gao MD, Guangxi Li MD, PhD, Tomas Kara MD, PhD and Virend K. Somers MD, PhD. Association Between Hypoxemia and Mortality in Patients With COVID-19. Mayo Clinic Proceedings, 2020-06-01, Volume 95, Issue 6, Pages 1138-1147.

Paper assesing severity of illness of Covid-19 patient, in which pulse oximeter oxygen saturation being <93% at rest was used as an indicator of a serious illness:
- Pingzheng Mo, Yuanyuan Xing, Yu Xiao, Liping Deng, Qiu Zhao, Hongling Wang, Yong Xiong, Zhenshun Cheng, Shicheng Gao, Ke Liang, Mingqi Luo, Tielong Chen, Shihui Song, Zhiyong Ma, Xiaoping Chen, Ruiying Zheng, Qian Cao, Fan Wang, Yongxi Zhang. Clinical characteristics of refractory COVID-19 pneumonia in Wuhan, China, Clinical Infectious Diseases, ciaa270

NiH Covid guidelines 23 and 24 rationalize supplemental oxygen due to weak evidence of its connection to Covid and strong evidence of the dangers of hypoxia:
- Alhazzani, W., Møller, M. H., Arabi, Y. M., Loeb, M., Gong, M. N., Fan, E., Oczkowski, S., Levy, M. M., Derde, L., Dzierba, A., Du, B., Aboodi, M., Wunsch, H., Cecconi, M., Koh, Y., Chertow, D. S., Maitland, K., Alshamsi, F., Belley-Cote, E., Greco, M., … Rhodes, A. (2020). Surviving Sepsis Campaign: guidelines on the management of critically ill adults with Coronavirus Disease 2019 (COVID-19). Intensive care medicine, 46(5), 854–887. https://doi.org/10.1007/s00134-020-06022-5
