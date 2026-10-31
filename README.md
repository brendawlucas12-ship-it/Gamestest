# Castle World · As aventuras de Lucas Yem

Versão aprimorada do HTML enviado pelo usuário, com as 14 etapas, guardiões, segredos, montarias e corrida bônus preservados.

## Jogar

Abra `index.html` em um navegador atualizado com suporte a WebGL. Imagens, áudio e Three.js estão incorporados: o jogo não precisa de conexão com a internet.

Para desenvolver, também é possível servir esta pasta:

```sh
cd /workspace/Gamestest
python3 -m http.server 8000 --bind 127.0.0.1
```

O progresso e a preferência de som ficam salvos neste navegador. O salvamento pode não estar disponível em modo privado ou se o armazenamento local estiver bloqueado.

## Controles

| Ação | Teclado |
| --- | --- |
| Andar / direção na corrida | ← → ou A D |
| Pular / acelerar na corrida | Espaço, ↑ ou W |
| Entrar no cano / frear | ↓ ou S |
| Ação da montaria / nitro | X |
| Sair da montaria | C |
| Pausar / continuar | P ou Esc |
| Alternar som | M |
| Tela cheia | F |

No celular, use os botões de toque. É possível andar e pular simultaneamente. O modo horizontal oferece uma área de jogo maior; a orientação vertical também é permitida. No mapa, selecione uma etapa e use **Explorar fase**. A corrida é desbloqueada ao concluir a primeira etapa.

## Alterações

- Nova tela inicial, guia de controles e menus com paleta de fantasia em verde, marfim e dourado.
- Mapa alinhado à arte, marcadores de progresso, cadeados e botão de entrada.
- HUD, diálogos, indicadores de poderes e seleção de carros redesenhados.
- Cenário com escala e enquadramento corrigidos, maior definição, iluminação e materiais ajustados.
- Entrada multitouch, teclas simultâneas e pausa ao perder o foco ou trocar de aba.
- Preferência de som persistente, validação de dados salvos e limpeza de recursos gráficos ao trocar de fase.

O código principal está no próprio `index.html`. Não é necessário instalar pacotes ou executar um build. A biblioteca Three.js r128 está incorporada com seu aviso de licença MIT.
