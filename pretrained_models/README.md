# Pretrained models

Here you can find some pretrained models over interesting datasets:

## Eric Satie's 2 hours music

I used the album [Music For Airports](https://www.youtube.com/watch?v=vNwYtllyt3Q) and a [1 hour extended version of An Ending (Ascent)](https://www.youtube.com/watch?v=alo3KFRfLvE).

To generate 16000 (1 second, 16kHz) samples from this pre-trained model:

<iframe width="100%" height="166" scrolling="no" frameborder="no" allow="autoplay" src="https://w.soundcloud.com/player/?url=https%3A//api.soundcloud.com/tracks/1004144023&color=%23ff5500&auto_play=false&hide_related=false&show_comments=true&show_user=true&show_reposts=false&show_teaser=true"></iframe><div style="font-size: 10px; color: #cccccc;line-break: anywhere;word-break: normal;overflow: hidden;white-space: nowrap;text-overflow: ellipsis; font-family: Interstate,Lucida Grande,Lucida Sans Unicode,Lucida Sans,Garuda,Verdana,Tahoma,sans-serif;font-weight: 100;"><a href="https://soundcloud.com/nschmidtg" title="nschmidtg" target="_blank" style="color: #cccccc; text-decoration: none;">nschmidtg</a> · <a href="https://soundcloud.com/nschmidtg/brian-eno-deeplearning-wavenet-generation" title="Brian Eno DeepLearning Wavenet generation" target="_blank" style="color: #cccccc; text-decoration: none;">Brian Eno DeepLearning Wavenet generation</a></div>

``` cd .. && python generate.py --wav_out_path=pretrained_models/brian_eno_generated.wav --samples=16000 pretrained_models/brian-eno-2-hours-123122-steps/model.ckpt-123122 ```

## Rhodes keyboard

I used a 1 hour youtube video of [Ikumi Ogasawara’s remarkable interpretation of well-known Pop songs](https://www.youtube.com/watch?v=EFLmGlQLavE) in her Rhodes keyboard

To generate 16000 (1 second, 16kHz) samples from this pre-trained model:

``` cd .. && python generate.py --wav_out_path=pretrained_models/rhodes_generated.wav --samples=16000 pretrained_models/rhodes-1-hour-123952-steps/model.ckpt-123952 ```

