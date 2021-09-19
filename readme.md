
| Classe de Caractere |                   Descrição                    | Equivalência I  | Equivalência II  |    Equivalência III    |
|---------------------|------------------------------------------------|-----------------|------------------|------------------------|
| .                   | Um caractere que não seja o \n                 |                 |                  |                        |
| \d                  | Um dígito                                      | [0-9]           | [^\D]            |                        |
| \D                  | Um caractere que não seja um dígito            | [^0-9]          | [^\d]            |                        |
| \s                  | Um caractere de espaço em branco               | [\t\n\v\r\f]    | [^\S]            | [\x09\x0a\x0b\x0c\0d]  |
| \S                  | Um caractere que não seja um espaço em branco  | [^\t\n\v\r\f]   | [^\s]            | [^\x09\x0a\x0b\x0c\0d] |

