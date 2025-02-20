# sistema-seguro-comunicacao

O objetivo deste projeto é implementar um sistema de comunicação seguro, focado na proteção das credenciais dos usuários e das mensagens armazenadas, utilizando tecnologias modernas de criptografia e autenticação. As principais ferramentas e técnicas utilizadas são:

bcrypt (Hashing seguro de senhas)
  As senhas dos usuários serão armazenadas de forma segura utilizando o algoritmo bcrypt, que realiza o hashing com um alto custo computacional, dificultando ataques de força bruta e garantindo que as senhas não sejam armazenadas em texto simples.

PyJWT (Autenticação via Tokens JWT)
  O sistema implementará autenticação usando Tokens JWT (JSON Web Token), garantindo que os usuários possam acessar recursos de forma segura sem a necessidade de sessões persistentes, proporcionando uma solução escalável e eficiente para autenticação em aplicações web.

cryptography (Implementação de AES e RSA)
  A biblioteca cryptography será utilizada para a implementação de criptografia simétrica (AES) e criptografia assimétrica (RSA). O AES será empregado para a criptografia de mensagens entre os usuários de forma rápida e eficiente, enquanto o RSA será utilizado para o gerenciamento seguro de chaves e para garantir a confidencialidade das mensagens trocadas.
