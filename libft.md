Frequent Reasons to fail the project:

| Fail Reason                                                                                                 | Failcount |
| ----------------------------------------------------------------------------------------------------------- | --------- |
| Calloc - when nmemb or size is 0, the function returned NULL instead of malloc(0) (do not trust the manual) | 1         |
| Calloc - should protect against int over flow when multiplying nmemb and size                               | 1         |
| Makefile - commands can be used multiple times. for clean: rm ${OBJ} fails                                  | 1         |
| ft_split - must return individual malloc for each string. storing all strings in one malloc will fail       | 1         |
