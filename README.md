# spectator-models

Unmodified copies of third-party speech model files that BetterDocket Spectator downloads on first run. They are mirrored here so the files Spectator verifies by size and SHA-256 do not change underneath it. Nothing in this repository is authored by BetterDocket; each file belongs to its publisher and is redistributed under its own licence.

Files are attached to the [releases](../../releases). Published assets are never replaced: a changed file gets a new release tag.

| File | Model | Publisher | Licence | Obtained from |
| --- | --- | --- | --- | --- |
| `sherpa-onnx-nemo-parakeet-tdt-0.6b-v3-int8.tar.bz2` | Parakeet-TDT 0.6B v3 (int8 ONNX export) | NVIDIA; export by k2-fsa/sherpa-onnx | [CC BY 4.0](https://huggingface.co/nvidia/parakeet-tdt-0.6b-v3) | k2-fsa/sherpa-onnx release `asr-models` |
| `sherpa-onnx-whisper-tiny.tar.bz2` | Whisper tiny (ONNX export) | OpenAI; export by k2-fsa/sherpa-onnx | [MIT](https://github.com/openai/whisper/blob/main/LICENSE) | k2-fsa/sherpa-onnx release `asr-models` |
| `sherpa-onnx-pyannote-segmentation-3-0.tar.bz2` | pyannote segmentation 3.0 (ONNX export) | pyannote; export by k2-fsa/sherpa-onnx | [MIT](https://huggingface.co/pyannote/segmentation-3.0) | k2-fsa/sherpa-onnx release `speaker-segmentation-models` |
| `nemo_en_titanet_small.onnx` | TitaNet small (ONNX export) | NVIDIA NeMo; export by k2-fsa/sherpa-onnx | [Apache 2.0](https://github.com/NVIDIA/NeMo/blob/main/LICENSE) | k2-fsa/sherpa-onnx release `speaker-recongition-models` |

## SHA-256

```
1495e91b59d7fc53ddca91f3431758ec99f8fa253fdb0e1e851be0f72b14b0f9  sherpa-onnx-nemo-parakeet-tdt-0.6b-v3-int8.tar.bz2
c46116994e539aa165266d96b325252728429c12535eb9d8b6a2b10f129e66b1  sherpa-onnx-whisper-tiny.tar.bz2
24615ee884c897d9d2ba09bb4d30da6bb1b15e685065962db5b02e76e4996488  sherpa-onnx-pyannote-segmentation-3-0.tar.bz2
ad4a1802485d8b34c722d2a9d04249662f2ece5d28a7a039063ca22f515a789e  nemo_en_titanet_small.onnx
```
