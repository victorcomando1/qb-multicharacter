# qb-multicharacter  
Multi Character Feature for QB-Core Framework :people_holding_hands:

**PT-BR:**  
Este fork foi criado para corrigir um problema comum onde jogadores enfrentavam **tela preta ao entrar no servidor**. A correção ajusta o momento em que o personagem é carregado, evitando conflitos entre eventos `playerSpawned` e o carregamento do personagem.  
Além disso, o fork mantém o suporte à definição padrão do número de personagens por jogador, com base na licença Rockstar.

**EN:**  
This fork was created to fix a common issue where players were experiencing a **black screen when joining the server**. The fix adjusts the timing of character loading to avoid conflicts between `playerSpawned` events and character initialization.  
In addition, the fork retains support for setting the default number of characters per player based on their Rockstar license.

---

## License

    QBCore Framework  
    Copyright (C) 2021 Joshua Eger  

    This program is free software: you can redistribute it and/or modify  
    it under the terms of the GNU General Public License as published by  
    the Free Software Foundation, either version 3 of the License, or  
    (at your option) any later version.

    This program is distributed in the hope that it will be useful,  
    but WITHOUT ANY WARRANTY; without even the implied warranty of  
    MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the  
    GNU General Public License for more details.

    You should have received a copy of the GNU General Public License  
    along with this program.  If not, see <https://www.gnu.org/licenses/>

---

## Dependencies / Dependências

- [qb-core](https://github.com/qbcore-framework/qb-core)  
- [qb-spawn](https://github.com/qbcore-framework/qb-spawn) – Spawn selector / Seletor de spawn  
- [qb-apartments](https://github.com/qbcore-framework/qb-apartments) – Dá um apartamento após criação do personagem  
- [qb-clothing](https://github.com/qbcore-framework/qb-clothing) – Criação e salvamento de roupas  
- [qb-weathersync](https://github.com/qbcore-framework/qb-weathersync) – Ajuste de clima durante a criação

---

## Screenshots
![Character Selection](https://cdn.discordapp.com/attachments/934470871333105674/1014215694394589294/unknown.png)  
![Character Registration](https://cdn.discordapp.com/attachments/934470871333105674/1014215687700488304/unknown.png)

---

## Features / Funcionalidades

- Criação de até 5 personagens e possibilidade de excluí-los.  
- Visualização de informações do personagem na tela de seleção.

---

## Installation / Instalação

### Manual

- Baixe o script e coloque-o na pasta `[qb]`.
- Adicione o seguinte ao `server.cfg` ou `resources.cfg`:

```bash
ensure qb-core
ensure qb-multicharacter
ensure qb-spawn
ensure qb-apartments
ensure qb-clothing
ensure qb-weathersync
