# Turnline local AI model mirrors

These are unmodified mirrors of open models for Turnline's optional local AI. Turnline tries Hugging Face first and uses these files only when Hugging Face can't be reached.

| Model | License | Upstream source |
|---|---|---|
| Phi-3.5-mini-instruct (Q4_K_M GGUF) | MIT | https://huggingface.co/bartowski/Phi-3.5-mini-instruct-GGUF/blob/2e8df1e9c43bb568a22a0e51c2c222048850618d/Phi-3.5-mini-instruct-Q4_K_M.gguf (model: https://huggingface.co/microsoft/Phi-3.5-mini-instruct) |
| Qwen2.5-1.5B-Instruct (q4_k_m GGUF) | Apache-2.0 | https://huggingface.co/Qwen/Qwen2.5-1.5B-Instruct-GGUF/blob/91cad51170dc346986eccefdc2dd33a9da36ead9/qwen2.5-1.5b-instruct-q4_k_m.gguf |

License texts: `Phi-3.5-mini-instruct.LICENSE` (MIT), `qwen2.5-1.5b-instruct.LICENSE` (Apache-2.0).

## sha256 pins (full files)

- `Phi-3.5-mini-instruct-Q4_K_M.gguf` (2393232672 bytes): `e4165e3a71af97f1b4820da61079826d8752a2088e313af0c7d346796c38eff5`
  Published as `.part001` (2000000000 bytes) and `.part002` (393232672 bytes) because of GitHub's 2 GB asset limit. `cat part001 part002` reproduces the pin.
- `qwen2.5-1.5b-instruct-q4_k_m.gguf` (1117320736 bytes): `6a1a2eb6d15622bf3c96857206351ba97e1af16c30d7a74ee38970e434e9407e`
- `Phi-3.5-mini-instruct.LICENSE`: `fa8235e5b48faca34e3ca98cf4f694ef08bd216d28b58071a1f85b1d50cb814d`
- `qwen2.5-1.5b-instruct.LICENSE`: `832dd9e00a68dd83b3c3fb9f5588dad7dcf337a0db50f7d9483f310cd292e92e`

Files are in the `models-v1` release.
