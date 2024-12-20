# MSS-Data-Augmentation
Musical Source Separation(MSS) is the process of separating stems from a track.
For example, given a music waveform with multiple instruments/audio sources,
MSS ouputs just the waveform for one source such as the tracks vocals. MSS has
been actively researched for decades with numerous models and different target
sources. However, training data for MSS is difficult to obatain as it requires tracks
with pre-separated sources. Many of the highest preforming models only train
on the MUSDB-18 dataset which only has 150 tracks. We aim to explore data
generation and augmentation techniques to create a larger training dataset and
investigate the preformance impact on existing models.

See MSS-FinalReport.pdf for the report.
