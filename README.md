<div style="font-size: 1.5rem;">
  <a href="./README.md">中文</a> |
  <a href="./README.en.md">English</a>
</div>
</br>
# OpenAI Cookbook

OpenAI Cookbook 分享了使用 [OpenAI API] 完成常見任務的範例代碼。

要運行這些範例，您需要一個 OpenAI 帳戶和相關的 API 金鑰 ( [創建免費帳戶][api signup] )。

大部分的代碼範例都是用 Python 編寫的，雖然這些概念也可以應用到任何語言中。

## 最近新增 🆕 ✨

- [如何格式化 ChatGPT 模型的輸入](examples/How_to_format_inputs_to_ChatGPT_models.ipynb) [2023年3月1日]
- [使用 Redis 的向量數據庫進行嵌入搜索](https://github.com/openai/openai-cookbook/tree/main/examples/vector_databases/redis) [2023年2月15日]
- [使用嵌入進行網站問答](https://github.com/openai/openai-cookbook/tree/main/apps/web-crawl-q-and-a) [2023年2月11日]
- [使用嵌入進行檔案問答](https://github.com/openai/openai-cookbook/tree/main/apps/file-q-and-a) [2023年2月11日]
- [在 Weights & Biases 中可視化嵌入](https://github.com/openai/openai-cookbook/blob/main/examples/Visualizing_embeddings_in_W%26B.ipynb) [2023年2月9日]
- [使用 Pinecone 進行檢索增強生成式問答](https://github.com/openai/openai-cookbook/blob/main/examples/vector_databases/pinecone/Gen_QA.ipynb) [2023年2月8日]

## 指南和範例

- API 使用
  - [如何處理速率限制](examples/How_to_handle_rate_limits.ipynb)
    - [避免觸發速率限制的並行處理腳本示例](examples/api_request_parallel_processor.py)
  - [如何使用 tiktoken 計算令牌數量](examples/How_to_count_tokens_with_tiktoken.ipynb)
  - [如何流式傳輸完成結果](examples/How_to_stream_completions.ipynb)
- ChatGPT
  - [如何格式化 ChatGPT 模型的輸入](examples/How_to_format_inputs_to_ChatGPT_models.ipynb)
- GPT-3
  - [指南：如何使用大型語言模型](how_to_work_with_large_language_models.md)
  - [指南：提高可靠性的技巧](techniques_to_improve_reliability.md)
  - [如何使用多步提示編寫單元測試](examples/Unit_test_writing_using_a_multi-step_prompt.ipynb)
  - [文本寫作範例](text_writing_examples.md)
  - [文本解釋範例](text_explanation_examples.md)
  - [文本編輯範例](text_editing_examples.md)
  - [代碼寫作範例](code_writing_examples.md)
  - [代碼解釋範例](code_explanation_examples.md)
  - [代碼編輯範例](code_editing_examples.md)
- 嵌入
  - [文本比較範例](text_comparison_examples.md)
  - [如何獲取嵌入](examples/Get_embeddings.ipynb)
  - [使用嵌入進行問答](examples/Question_answering_using_embeddings.ipynb)
  - [使用嵌入進行語義搜索](examples/Semantic_text_search_using_embeddings.ipynb)
  - [使用嵌入進行推薦](examples/Recommendation_using_embeddings.ipynb)
  - [聚類嵌入](examples/Clustering.ipynb)
  - [在二維中可視化嵌入](examples/Visualizing_embeddings_in_2D.ipynb) 或 [三維中](examples/Visualizing_embeddings_in_3D.ipynb)
  - [嵌入長文本](examples/Embedding_long_inputs.ipynb)
- GPT-3 微調
  - [指南：微調 GPT-3 分類文本的最佳實踐](https://docs.google.com/document/d/1rqj7dkuvl7Byd5KQPUJRxc19BJt8wo0yHNwK84KfU3Q/edit)
  - [微調分類](examples/Fine-tuned_classification.ipynb)
- DALL-E
  - [如何使用 DALL-E 生成和編輯圖像](examples/dalle/Image_generations_edits_and_variations_with_DALL-E.ipynb)
- Azure OpenAI (Microsoft Azure 的替代 API)
  - [如何從 Azure OpenAI 獲取完成結果](examples/azure/completions.ipynb)
  - [如何從 Azure OpenAI 獲取嵌入](examples/azure/embeddings.ipynb)
  - [如何使用 Azure OpenAI 微調 GPT-3](examples/azure/finetuning.ipynb)
- 應用程式
  - [檔案問答](apps/file-q-and-a/)
  - [網頁爬蟲問答](apps/web-crawl-q-and-a)

## 相關資源

除了這裡的代碼範例外，您還可以從以下資源學習關於 [OpenAI API]：

- 在 [OpenAI Playground] 中試用 API
- 在 [OpenAI Documentation] 中閱讀有關 API 的資訊
- 在 [OpenAI Community Forum] 中討論 API
- 在 [OpenAI Help Center] 中尋求幫助
- 在 [OpenAI Examples] 中查看範例提示
- 體驗免費的研究預覽版本的 [ChatGPT]
- 保持更新，關注 [OpenAI Blog]

## 貢獻

如果您有任何想要看到的範例或指南，歡迎在 [issues page] 上提出建議。

[chatgpt]: https://chat.openai.com/
[openai api]: https://openai.com/api/
[api signup]: https://beta.openai.com/signup
[openai playground]: https://beta.openai.com/playground
[openai documentation]: https://beta.openai.com/docs/introduction
[openai community forum]: https://community.openai.com/top?period=monthly
[openai help center]: https://help.openai.com/en/
[openai examples]: https://beta.openai.com/examples
[openai blog]: https://openai.com/blog/
[issues page]: https://github.com/openai/openai-cookbook/issues
