# Ficha Técnica do Modelo (Hugging Face)

*Item 3 dos entregáveis. Campos exigidos pela seção 5.3 da AV1.*

| Critério | Preencher |
|---|---|
| Organização / nome completo do modelo | Meta // meta-llama/Llama-3.2-3B-Instruct |
| URL do model card | https://huggingface.co/meta-llama/Llama-3.2-3B-Instruct |
| Quantidade total de parâmetros (modelo-base) | 3.21B |
| Finalidade (base, instruct, chat, código, multilíngue...) | Instruct (diálogo e cumprimento de instruções) |
| Idioma(s) suportado(s) | Inglês, Português, Espanhol, Francês, Alemão, Italiano, Hindi, Tailandês |
| Licença (permissões, restrições, obrigações) | Llama 3.2 Community License. |
| Formato (GGUF, Safetensors, GGML...) | GGUF |
| Quantização (Q4, Q5, Q8, FP16...) | Q4_K_M |
| Janela máxima de contexto | 131072 tokens |
| Tamanho dos arquivos baixados | 2.02GB |
| Requisitos de hardware (RAM, VRAM, CPU/GPU) | RAM: Mínimo de 8 GB de RAM no sistema. VRAM: Mínimo de 4 GB de VRAM caso executado em GPU dedicada. CPU/GPU: CPU x86_64 com suporte a AVX2 para execução em CPU; ou GPUs NVIDIA/AMD compatíveis com CUDA/ROCm. |
| Compatibilidade (Ollama / conversão compatível) | Totalmente compatível com Ollama |
| Documentação (clareza do model card, exemplos, limitações) | [preencher] |
| Riscos e limitações (viés, confabulação, segurança, privacidade) | [preencher] |

**Justificativa da escolha (até 100 palavras):**
 O modelo Llama3.2-3B oferece um bom equilíbrio de qualidade de respostas e requisito de hardware, facilitando a observação de chamadas de sistema e uso de recursos de hardware sem esgotar o desempenho computacional local. A escolha de quantização Q4 oferece flexibilidade quanto ao tamanho do modelo e possibilita o estudo entre diferentes níveis de quantização do mesmo modelo para comparações diretas.
