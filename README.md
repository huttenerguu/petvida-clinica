# PetVida – Clínica Veterinária e Estética Pet

Site institucional simples (HTML e CSS) da PetVida, com apresentação dos serviços e um formulário de pedido de agendamento.

**Site publicado:** `https://huttenerguu.github.io/petvida-clinica/` *(substitua após ativar o GitHub Pages)*

## 1. Briefing do problema

A PetVida é uma clínica veterinária e centro de estética pet de bairro, fundada pelo Dr. Gabriel Santos e pela Dra. Camila Paes. Oferece consultas, vacinação, cirurgias de pequeno porte e banho e tosa.

Todo o agendamento é feito em uma agenda de papel, por duas recepcionistas. Com mais de 30 banhos por dia e consultas sobrepostas, surgem:

- choques de horário;
- tutores que esquecem a data do banho ou da vacina, deixando lacunas na agenda;
- tempo perdido procurando históricos em pastas físicas;
- perda de receita por horários ociosos e falta de lembretes de retorno.

## 2. Justificativa da solução: site

Escolhi um **site institucional** porque é a porta de entrada mais simples para o tutor: abre em qualquer celular, não exige instalação e pode ser divulgado por link e QR code na recepção. Ele apresenta os serviços, mostra o diferencial da clínica (cuidado estético ligado ao histórico de saúde) e recebe pedidos de agendamento.

Esta versão é propositalmente enxuta (apenas HTML e CSS). O formulário é um **protótipo** e ainda não envia dados. Os próximos passos naturais são um sistema de agenda para a recepção, lembretes automáticos e prontuário digital.

## 3. Protótipo / telas

Página única com as seções:

| Seção | Função |
|---|---|
| Início | Mensagem principal e botão de agendamento |
| Serviços | Consultas, vacinação, cirurgias e banho e tosa |
| Como funciona o agendamento | Três passos: serviço, horário, lembrete |
| Equipe | Sócios e time da clínica |
| Agende seu horário | Formulário de pedido |

## 4. Arquitetura

```
petvida-clinica/
├── index.html   # estrutura e conteúdo
├── style.css    # estilos (responsivo, sem frameworks)
├── .gitignore
├── LICENSE
└── README.md
```

Sem dependências, sem build e sem backend. Nenhuma credencial ou chave de API é usada.

## 5. Como executar

**Localmente:** baixe ou clone o repositório e abra o `index.html` no navegador.

```bash
git clone https://github.com/SEU-USUARIO/petvida-clinica.git
cd petvida-clinica
# abra index.html no navegador
```

**Publicar no GitHub Pages:** no repositório, vá em *Settings → Pages*, escolha a branch `main` e a pasta `/ (root)`, e salve.

## 6. Licença

Distribuído sob a licença MIT. Veja o arquivo [LICENSE](LICENSE).
