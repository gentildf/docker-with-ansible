# Ansible for Docker

Este projeto contém um playbook Ansible para automatizar a instalação do Docker, Docker Compose e configurar um ambiente Dockerizado em sistemas baseados em Linux (Ubuntu).

## Estrutura do Projeto

```bash
ansible-for-docker/
├── inventories/
│   └── localhost.yml         # Arquivo de inventário para localhost
├── playbooks/
│   └── setup_docker.yml      # Playbook principal para configurar Docker
├── roles/
│   └── docker/
│       ├── tasks/
│       │   └── main.yml      # Tarefas do role Docker
│       ├── files/            # Arquivos adicionais (se necessário)
│       └── templates/        # Templates adicionais (se necessário)
└── README.md                 # Este arquivo
