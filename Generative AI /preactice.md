# 1. Tokenize a paragraph (e.g. with tiktoken) and inspect how words map to tokens; note the token count.

### gpt-4o :

```

hello world this is tiktoken tokenizer which provides free token distribution between multiple models.
------------------------------------------------------------------------------------------------------
24912, 2375, 495, 382, 260, 8251, 2488, 99665, 1118, 6008, 2240, 6602, 12545, 2870, 7598, 7015, 13

<|im_start|>assistant<|im_sep|>You are a helpful assistant<|im_end|><|im_start|>
user<|im_sep|>create the new peregraph<|im_end|><|im_start|>assistant<|im_sep|>
------------------------------------------------------------------------------------------------------
200264, 173781, 200266, 3575, 553, 261, 10297, 29186, 200265, 200264, 1428, 200266, 2537, 290, 620, 63016, 7978, 200265, 200264, 173781, 200266

```

### microsoft/phi-2 :

```

hello world this is tiktoken tokenizer which provides free token distribution between multiple models.
------------------------------------------------------------------------------------------------------
31373, 995, 428, 318, 256, 1134, 30001, 11241, 7509, 543, 3769, 1479, 11241, 6082, 1022, 3294, 4981, 13

<|im_start|>assistant<|im_sep|>You are a helpful assistant<|im_end|><|im_start|>
user<|im_sep|>create the new peregraph<|im_end|><|im_start|>assistant<|im_sep|>
------------------------------------------------------------------------------------------------------
27, 91, 320, 62, 9688, 91, 29, 562, 10167, 27, 91, 320, 62, 325, 79, 91, 29, 1639, 389, 257, 7613, 8796, 27, 91, 320, 62, 437, 91, 6927, 91, 320, 62, 9688, 91, 29, 198, 7220, 27, 91, 320, 62, 325, 79, 91, 29, 17953, 262, 649, 279, 567, 34960, 27, 91, 320, 62, 437, 91, 6927, 91, 320, 62, 9688, 91, 29, 562, 10167, 27, 91, 320, 62, 325, 79, 91, 29

```
## 2. Send the same prompt to 2–3 models (different providers or sizes).


