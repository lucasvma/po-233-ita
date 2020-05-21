## Um reconhecimento de modulação digital baseado em característica para rede assistidas por VANT em um aprendizado de máquina
<!--- These are examples. See https://shields.io for others or to customize this set of shields. You might want to include dependencies, project status and licence info here --->
![GitHub watchers](https://img.shields.io/github/watchers/flaviol-souza/po-233-ita?style=social)
![GitHub repo size](https://img.shields.io/github/repo-size/flaviol-souza/po-233-ita)
![Twitter Follow](https://img.shields.io/twitter/follow/flaviolsouza?style=social)
#### This is the result of the work home of the PO-233 discipline at [ITA](http://ita.br/)

## Description
Inspired by Matlab`s example [Modulation Classification with Deep Learning](https://www.mathworks.com/help/comm/examples/modulation-classification-with-deep-learning.html?s_tid=mwa_osa_a), this project has goals to identified the modulation schema by a machine learning. Implemented during the PO-233 discipline at ITA, I leave here the artifacts to reproduce the experiment.

Basically we generate 1000 frames to each digital modulation (8-PSK, 16-QAM, 64-QAM, BPSK, CPFSK, GFSK, QPSK and PAM4) on Matlab according to [Modulation Classification with Deep Learning](https://www.mathworks.com/help/comm/examples/modulation-classification-with-deep-learning.html?s_tid=mwa_osa_a).

![alt text](https://github.com/flaviol-souza/po-233-ita/blob/master/images/waves.png)

The frames produced has noises into signals as can be observed in Waves with Noises 1 and 2 figures.
![alt-text-1](https://github.com/flaviol-souza/po-233-ita/blob/master/images/layout1.png "Noises Waves 1")  ![alt-text-2](https://github.com/flaviol-souza/po-233-ita/blob/master/images/layout2.png "Noises Waves 2")

## Build With
* Matlab (R2020b)
* Jupyter Lab 
    * Python
    * R

## Installation

Use the package manager R to install foobar.

```bash
install.packages("R.matlab")
install.packages("wavelets")
install.packages("tuneR")
install.packages("data.table")
install.packages("GENEAread")
install.packages("constellation")
```

## Usage

To use <project_name>, follow these steps:

Step 1
* Open the Matlab and execute the waveform_generation.m script
* Copy the files results (frame*.mat) to database/origin 

```
<usage_example>
```

Add run commands and examples you think users will find useful. Provide an options reference for bonus points!

## Contributing 
<!--- If your README is long or you have some specific process or steps you want contributors to follow, consider creating a separate CONTRIBUTING.md file--->
To contribute to <project_name>, follow these steps:

1. Fork this repository.
2. Create a branch: `git checkout -b <branch_name>`.
3. Make your changes and commit them: `git commit -m '<commit_message>'`
4. Push to the original branch: `git push origin <project_name>/<location>`
5. Create the pull request.

Alternatively see the GitHub documentation on [creating a pull request](https://help.github.com/en/github/collaborating-with-issues-and-pull-requests/creating-a-pull-request).

## Contributors
Thanks to the following people who have contributed to this project:
* Flavio Souza [e-mail](mailto:flavio.souza@ifsp.edu.br) or [web profile](https://www.flaviosouza.net) 
    * Felipe Verri (_Orientador_) [e-mail](mailto:verri@ita.br) or [web profile](http://www.comp.ita.br/~verri/) 
    * Lourenço Junior (_Orientador_) [e-mail](mailto:ljr@ita.br)

## License
[APACHE](https://www.apache.org/licenses/LICENSE-2.0)