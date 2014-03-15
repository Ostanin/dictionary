Dictionary
==========

Vocabulary database (Russian, English, Chinese). Using json format

Now in base: 
* 0 Russian words;
* 0 English words;
* 0 Chinese words;

```json
{
  "original word" {
                    "interpreting word" : "interpretation of the word in the native language",
                    "translation" {
                                    "russian" : "оригинальное слово, исходное слово",
                                    "english" : "original word",
                                    "chinese" : "原詞",
                    }
                    "tags" {
                             "tag 1" : "true",
                             "tag 2" : "false",
                    }
                    "phrases" {
                               "offical phrases" {
                                                  "russian" : "",
                                                  "english" : "",
                                                  "chinese" : "",
                               }
                               "users phrases" {
                                                "link" : "",
                               }
                              }
                    "examples" {
                                "official examples" {
                                                     "russian" : "",
                                                     "english" : "",
                                                     "chinese" : "",
                                }
                                "users examples" {
                                                    "link" : "",
                                }
                    }
  }
}
