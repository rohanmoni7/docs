A API de verificação procura apenas por pushes no repositório onde o conjunto de verificação ou a execução de verificação foram criados. Pushes para um branch em um repositório bifurcado não foi detectado e retorna um array `pull_requests` vazio e um valor `null` para `head_branch`.