# Особенности сгенерированных описаний экспонатов по сравнению с названиями из музейной практики. 
## Данные

В репозитории размещены четыре таблицы с результатами работы мультимодальных моделей. Каждая таблица соответствует отдельному запуску модели и содержит музейные метаданные произведений, поля машинного описания и машинного названия, а также рассчитанное косинусное расстояние между музейным названием и названием, предложенным моделью.

Все файлы имеют единую структуру и могут быть сопоставлены между собой по музейным идентификаторам и основным полям метаданных.

| Файл | Модель | Источник модели |
|---|---|---|
| `paintings_gemma_with_cosine_distance.csv` | Google Gemma 4-e4b | [LM Studio](https://lmstudio.ai/models/google/gemma-4-e4b) |
| `paintings_mistral_with_cosine_distance.csv` | Mistral Small 3.2 24B Instruct 2506 Heretic v1.2-2 | [Hugging Face](https://huggingface.co/grayarea/Mistral-Small-3.2-24B-Instruct-2506-Heretic-v1.2-2) |
| `paintings_qwen3_6_with_cosine_distance.csv` | Qwen3.6 35B A3B GGUF, q4_k_s | [Hugging Face](https://huggingface.co/unsloth/Qwen3.6-35B-A3B-GGUF) |
| `paintings_qwen3_vl_with_cosine_distance.csv` | Qwen3-VL 8B Instruct, q8_0 | [Hugging Face](https://huggingface.co/Qwen/Qwen3-VL-8B-Instruct) |
