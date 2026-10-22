<p align="center"><img src="docs/assets/capa.svg" alt="Ponto a Ponto — sua foto vira gráfico de crochê" width="100%"></p>

<p align="center">
  <a href="https://pontoapontocroche.vercel.app/app/"><img alt="Abrir aplicativo" src="https://img.shields.io/badge/Abrir_aplicativo-d9694a?style=for-the-badge&amp;logo=googlechrome&amp;logoColor=white"></a>
  <a href="https://github.com/Bielicoman/pontoapontocroche/releases/latest"><img alt="Baixar última versão" src="https://img.shields.io/github/v/release/Bielicoman/pontoapontocroche?style=for-the-badge&amp;label=Baixar&amp;color=8fa98a"></a>
</p>

<p align="center"><b>Um ateliê de gráficos de crochê no seu aparelho.</b><br>Transforme fotos, escolha entre 1.000 desenhos e personalize cada cor antes de começar.</p>

<p align="center"><a href="#comece-aqui">Comece aqui</a> · <a href="#o-que-você-pode-fazer">Recursos</a> · <a href="#baixe-para-seu-aparelho">Downloads</a> · <a href="#veja-por-dentro">Veja por dentro</a></p>

## Comece aqui

**[Abrir Ponto a Ponto →](https://pontoapontocroche.vercel.app/app/)**

1. Escolha uma foto, um modelo pronto ou uma grade em branco.
2. Ajuste tamanho, fios e cores. Confira a medida usando a sua amostra.
3. Ative **Crochetar** para acompanhar as carreiras ou exporte o gráfico.

O editor funciona sem cadastro. Entre com e-mail e senha quando quiser sincronizar seus gráficos ou conversar com a Fia pela internet.

## O que você pode fazer

| Para criar | Para crochetar |
|---|---|
| Converter uma foto em uma grade de pontos | Contar pontos e acompanhar cada carreira |
| Buscar entre **1.000 desenhos diferentes** | Calcular dimensões pela sua amostra |
| Editar as cores e montar nomes ou frases | Estimar fio, consultar Tex e agulha |
| Ajustar o modelo antes de abrir no editor | Exportar **PDF, PNG e projeto editável** |
| Conversar com a **Fia**, com conta e conexão | Guardar projetos no aparelho e sincronizar na nuvem |

As cores são editáveis; variações de paleta não são contadas como novos desenhos. O editor e a biblioteca continuam disponíveis sem internet após o primeiro carregamento. As estimativas de tamanho e fio dependem da amostra e do material.

## Baixe para seu aparelho

| Seu aparelho | Instalação |
|---|---|
| **Windows 10/11 · 64 bits** | [Instalador](https://github.com/Bielicoman/pontoapontocroche/releases/latest/download/PontoAPonto-Windows.exe) · [Portátil](https://github.com/Bielicoman/pontoapontocroche/releases/latest/download/PontoAPonto-Windows-portatil.exe) |
| **Mac com chip Apple · macOS 12+** | [Baixar DMG para M1, M2, M3 e posteriores](https://github.com/Bielicoman/pontoapontocroche/releases/latest/download/PontoAPonto-Mac-arm64.dmg) |
| **Mac Intel · macOS 12+** | [Baixar DMG Intel](https://github.com/Bielicoman/pontoapontocroche/releases/latest/download/PontoAPonto-Mac-x64.dmg) |
| **Android** | [Baixar APK](https://github.com/Bielicoman/pontoapontocroche/releases/latest/download/PontoAPonto-Android.apk) |
| **iPhone e iPad** | [Abrir no Safari](https://pontoapontocroche.vercel.app/app/) → Compartilhar → Adicionar à Tela de Início |
| **Qualquer computador** | [Usar no navegador](https://pontoapontocroche.vercel.app/app/) |

No Mac, use **Ajustes do Sistema → Privacidade e Segurança** para permitir a primeira abertura, caso seja solicitado. Os aplicativos de computador ainda não possuem certificado comercial de distribuição.

A Fia online conversa e cria imagens por modelos de IA gratuitos: Z-Image-Turbo no Hugging Face e, quando disponível, fila comunitária do AI Horde. Há cotas, filas e possíveis interrupções; nenhum plano pago é acionado automaticamente. Conta e internet são necessárias. Novo chat e histórico permitem retomar ou apagar conversas salvas neste aparelho. Os pedidos online passam por Vercel/Groq e pelos provedores de imagem; a sincronização de projetos usa Firebase. A opção de IA local nos instaladores de computador depende de baixar modelos.

## Veja por dentro

### Um ponto de partida simples

![Tela inicial do aplicativo](docs/assets/inicio.png)

### Uma biblioteca para explorar

![Biblioteca de modelos com filtros](docs/assets/biblioteca.png)

### Seu gráfico, suas cores

![Editor com gráfico, cores e carreiras](docs/assets/editor.png)

## Ajuda e novidades

- [Site e instruções de instalação](https://pontoapontocroche.vercel.app/)
- [Última versão e histórico de downloads](https://github.com/Bielicoman/pontoapontocroche/releases)
- [Relatar um problema](https://github.com/Bielicoman/pontoapontocroche/issues/new/choose)

<p align="center"><sub>Criado por Alex Ascencio · Bielicoman</sub></p>

## Desenvolvimento

O código-fonte está organizado em `web/`, `api/`, `lib/`, `desktop/`, `android/` e `tools/`. Consulte o [guia de desenvolvimento e publicação](docs/DEVELOPMENT.md) para comandos, arquitetura, IA local e verificações. Os instaladores públicos ficam em um repositório separado.

## Transparência e licença

O código e a documentação originais são disponibilizados sob a [licença MIT](LICENSE), preservados os direitos de terceiros. Consulte a [central de transparência](https://pontoapontocroche.vercel.app/app/legal/), com privacidade, termos, armazenamento, uso de IA, direitos e exclusão de dados, segurança e créditos.

Contato: [ascencioalexgabriel@gmail.com](mailto:ascencioalexgabriel@gmail.com).
