# Set up

## CUDA のインストール

https://developer.nvidia.com/cuda-10.0-download-archive?target_os=MacOSX&target_arch=x86_64&target_version=1013&target_type=dmglocal
より cuda_10.0.130_mac.dmg をダウンロードして、インストール

## Python 環境の構築

```{.bash}
pyenv local 3.9.0
poetry install
```

# Reference

- [Amazon SageMaker と AutoGluon-Text で自然言語処理モデルを作ろう](https://aws.amazon.com/jp/builders-flash/202009/natural-lang-processing-model/)
- [機械学習未経験者も良いモデルを作れる AutoGluon で「テキスト分類」をやってみた](https://acro-engineer.hatenablog.com/entry/2020/02/13/120000)
