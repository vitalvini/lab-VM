# lab-VM
detalhamento da criação de uma VM
2. Criando a Máquina Virtual

1. No menu lateral, clique em **Máquinas Virtuais**.
2. Clique em **+ Criar** > **Máquina Virtual**.
3. Preencha os campos:

- **Grupo de Recursos**: Crie ou selecione um existente.
- **Nome da VM**: Ex: `lab-vm-azure`.
- **Região**: Escolha uma próxima (ex: Brazil South).
- **Imagem**: Windows 11, Ubuntu 22.04 etc.
- **Tamanho**: Escolha um plano gratuito ou básico.
- **Usuário/Admin**: Nome e senha para acesso.

 4. Opções de Disco

Escolha SSD ou HD padrão. Para testes, o padrão é suficiente.

 5. Rede

- Deixe as configurações padrão (nova interface e grupo de segurança).
- Permita portas necessárias (RDP para Windows, SSH para Linux).
