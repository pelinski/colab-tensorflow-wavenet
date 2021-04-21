# Pretrained models

Here you can find some pretrained models over interesting datasets:

## Eric Satie's 2 hours music

I used the album [Music For Airports](https://www.youtube.com/watch?v=vNwYtllyt3Q) and a [1 hour extended version of An Ending (Ascent)](https://www.youtube.com/watch?v=alo3KFRfLvE).

To generate 16000 (1 second, 16kHz) samples from this pre-trained model:

``` cd .. && python generate.py --wav_out_path=pretrained_models/brian_eno_generated.wav --samples=16000 pretrained_models/brian-eno-2-hours-123122-steps/model.ckpt-123122 ```

## Rhodes keyboard

I used a 1 hour youtube video of [Ikumi Ogasawara’s remarkable interpretation of well-known Pop songs](https://www.youtube.com/watch?v=EFLmGlQLavE) in her Rhodes keyboard

To generate 16000 (1 second, 16kHz) samples from this pre-trained model:

``` cd .. && python generate.py --wav_out_path=pretrained_models/rhodes_generated.wav --samples=16000 pretrained_models/rhodes-1-hour-123952-steps/model.ckpt-123952 ```

## Dubstep music

I used a 10 hours youtube video of [6 hours of Dubstep music](https://www.youtube.com/watch?v=AvxBRHM9U9k)

To generate 16000 (1 second, 16kHz) samples from this pre-trained model:

``` cd .. && python generate.py --wav_out_path=pretrained_models/dubstep_generated.wav --samples=16000 pretrained_models/dubstep-10-hours-519900-steps/model.ckpt-519900 ```
