
| Classe de Caractere |                   Descrição                    | Equivalência I  |    Equivalência II     |
|---------------------|------------------------------------------------|-----------------|------------------------|
| .                   | Um caractere que não seja o \n                 |                 |                        |
| \d                  | Um dígito                                      | [0-9]           |                        |
| \D                  | Um caractere que não seja um dígito            | [^0-9]          | [^\d]                  |
| \s                  | Um caractere de espaço em branco               | [\t\n\v\r\f]    | [\x09\x0a\x0b\x0c\0d]  |
| \S                  | Um caractere que não seja um espaço em branco  | [^\t\n\v\r\f]   | [^\x09\x0a\x0b\x0c\0d] |
