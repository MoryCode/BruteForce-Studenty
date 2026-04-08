# Utilizando Kali Linux e Medusa para brute force e password spraying
Esse é meu projeto de brute force que estou estudando pela DIO utilizando Kali Linux e a ferramente Medusa.

Utilizei todos os scripts realizados nas videos aulas e coloquei em prática no meu VM com Kali e Metasplotable.
<img width="762" height="179" alt="image" src="https://github.com/user-attachments/assets/313962a2-82c2-4740-885e-8d56ba7b3816" />

Como orientado nas aulas consegui ter acesso ao IP da máquina e a conectaar a mesma rede.
<img width="738" height="413" alt="image" src="https://github.com/user-attachments/assets/b76244b9-9c04-411a-813c-d1ad5fc99ac2" />

Com o Kali realizei a criação de dois arquivos .txt para gerar os users e os passwords para o Brute Force controlado.
<img width="470" height="223" alt="image" src="https://github.com/user-attachments/assets/14bfc702-8096-4a87-b5c0-3ba9780acad7" />

Após a criação, iniciei os ataques de forma que toda tentativa me retornace como Falho ou Sucesso. Caso haja sucesso na invasão eu saberia o user e o password.
<img width="1295" height="425" alt="image" src="https://github.com/user-attachments/assets/02654351-408d-4c6f-95ed-3cf7e76dda46" />

Enumeração SMB e Password Spraying, o que seria isso?
SMB seria uma porta de entrada para ter acesso a máquinas e servers, ótimo para buscar vulnerabilidades e práticas de estudos que é o caso de agora.
Como faço para rodar isso no KaliLinux?
Digamos que você já tenha acesso a uma rede, nesse caso você terá que saber quais tipos de usuários estarão no servidor e assim utilizar o password spraying como no código abaixo: 

<img width="563" height="175" alt="image" src="https://github.com/user-attachments/assets/636fdd0e-eb76-47f0-9a24-04d099ea51f7" />

Esse código utilizamos o Enum4liux para enumerar os tipos de usuários do sistema.

<img width="924" height="809" alt="image" src="https://github.com/user-attachments/assets/2539f5e6-859c-485d-b57c-1aa140ada454" />

<img width="318" height="587" alt="image" src="https://github.com/user-attachments/assets/f85f3410-91c7-4af3-88bd-c0e9d39b13ff" />

Porque fazemos isso? Digamos que você teste várias senhas com vários tipos de usuarios, isso levaria tempo e mais erros. Enumerando os tipos de usuários você consegue ter mais sucesso na invasão e realizar o passwors spraying.

<img width="1255" height="245" alt="image" src="https://github.com/user-attachments/assets/1304f31d-d011-4bad-9ac6-5187ac424a2e" />

Notasse que ele me retorna com as tentativas e qual teve sucesso. Esse metódo diferente do brute force, ele tenta poucas senhas em vários usuários, isso impede que o sistema detecte qualquer tipo de movimentação suspeita e faz com que você tenha acesso de forma mais silenciosa e de forma inteligente.

# Obrigado pela atenção!
