# P.1203 — Repositories

## What is ITU-T P.1203?

ITU-T Rec. P.1203 is the **world's first standard** for measuring the **Quality of Experience of HTTP Adaptive Streaming** services.

P.1203 has been trained and validated on over a thousand video sequences, rated by human subjects, in order to deliver the best possible prediction of QoE for transmissions that contain initial loading, stalling, and quality variations.

## What software / data is available?

We developed an [implementation of the ITU-T Rec. P.1203 standard](https://github.com/itu-p1203/itu-p1203). It can be used together with the [codec extension](https://github.com/Telecommunication-Telemedia-Assessment/itu-p1203-codecextension) from our lab, to cover non-standard codecs.

An [open dataset](https://github.com/itu-p1203/open-dataset) was created for this model, which contains training and validation databases from the standardization procedure.


## Who are we?

The [Audiovisual Technology Group](https://www.tu-ilmenau.de/en/audio-visual-technology/) group is part of the Institute of Media Technology at TU Ilmenau, Germany, headed by Prof. Alexander Raake. The Audiovisual Technology Group (AVT) deals with the function, application and perception of audio and video equipment and systems.

The software was developed together with partners from Deutsche Telekom AG, Technische Universität Berlin, LM Ericsson.

## What is the license?

The P.1203 software is available for **non-commercial research purposes**. For a commercial license, the respective rights have to be obtained by the rights holders. See the [license statement](https://github.com/itu-p1203/itu-p1203/#license) for more information.

## Acknowledgement

If you use the software or data in your research, please include the link to the corresponding repositories and cite the following publications:

* Raake, A., Garcia, M.-N., Robitza, W., List, P., Göring, S., & Feiten, B. (2017). A bitstream-based, scalable video-quality model for HTTP adaptive streaming: ITU-T P.1203.1. In 2017 Ninth International Conference on Quality of Multimedia Experience (QoMEX). Erfurt.

        {% raw  %}
        @inproceedings{Raake2017,
        address = {Erfurt},
        author = {Raake, Alexander and Garcia, Marie-Neige and Robitza, Werner and List, Peter and Göring, Steve and Feiten, Bernhard},
        booktitle = {Ninth International Conference on Quality of Multimedia Experience (QoMEX)},
        doi = {10.1109/QoMEX.2017.7965631},
        isbn = {978-1-5386-4024-1},
        month = {May},
        publisher = {IEEE},
        title = {{A bitstream-based, scalable video-quality model for HTTP adaptive streaming: ITU-T P.1203.1}},
        url = {http://ieeexplore.ieee.org/document/7965631/},
        year = {2017}
        }
        {% endraw  %}


* Robitza, W., Göring, S., Raake, A., Lindegren, D., Heikkilä, G., Gustafsson, J., List, P., Feiten, B., Wüstenhagen, U., Garcia, M.-N., Yamagishi, K., Broom, S. (2018). HTTP Adaptive Streaming QoE Estimation with ITU-T Rec. P.1203 – Open Databases and Software. In 9th ACM Multimedia Systems Conference. Amsterdam.

        {% raw  %}
        @inproceedings{Robitza2018,
        address = {Amsterdam},
        author = {Robitza, Werner and Göring, Steve and Raake, Alexander and Lindegren, David and Heikkilä, Gunnar and Gustafsson, Jörgen and List, Peter and Feiten, Bernhard and Wüstenhagen, Ulf and Garcia, Marie-Neige and Yamagishi, Kazuhisa and Broom, Simon},
        booktitle = {9th ACM Multimedia Systems Conference},
        doi = {10.1145/3204949.3208124},
        isbn = {9781450351928},
        title = {{HTTP Adaptive Streaming QoE Estimation with ITU-T Rec. P.1203 – Open Databases and Software}},
        year = {2018}
        }
        {% endraw %}