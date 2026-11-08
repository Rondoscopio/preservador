![Rondoscópio, Preservador](assets/banner.webp)

# Preservador

Projeto do **Rondoscópio** no repositório **Rondoscopio/preservador**.

O Preservador pretende desenvolver softwares para que colaboradores credenciados mantenham cópias independentes e verificáveis dos acervos e das bases de dados cuja replicação tenha sido autorizada. O objetivo é reduzir a dependência do servidor principal e permitir a recuperação de informações em caso de perda, corrupção ou indisponibilidade.

## Propósito e resiliência

A memória documental de uma iniciativa de fiscalização não deve depender de um único servidor ou responsável. Enchentes, incêndios, interrupções de energia, falhas de hardware, ataques cibernéticos, sabotagem e tentativas de apagamento podem comprometer anos de trabalho.

A redundância também busca diminuir os efeitos de apreensões arbitrárias, intervenções abusivas e ações policiais ou judiciais ilegais que ameacem a continuidade do acervo. O projeto não se destina a impedir investigações legais nem o cumprimento de decisões judiciais legítimas.

A preservação depende de cópias distribuídas em ambientes independentes, verificação de integridade, histórico de versões e procedimentos testados de restauração. Multiplicar arquivos, por si só, não garante sua recuperação.

## Funcionamento previsto

Os colaboradores executarão um ou mais softwares que iniciarão a sincronização com os serviços do Rondoscópio, sem receber acesso direto ao banco de dados de produção.

A participação exigirá credenciamento e estabelecimento de confiança criptográfica, com verificação de chaves públicas e certificados, inclusive por procedimentos presenciais quando necessários. Chaves privadas não serão compartilhadas. A autorização de download não implicará acesso ao conteúdo de eventuais backups criptografados.

Somente conjuntos de dados autorizados poderão ser distribuídos. O tratamento de informações restritas deverá respeitar a proteção de fontes, a privacidade, a legislação aplicável e as obrigações de confidencialidade.

Este repositório armazenará apenas código-fonte, documentação, testes e configurações de exemplo. Não conterá backups, bancos de dados reais, credenciais, chaves privadas ou cópias do acervo.

**Projeto em planejamento.** O credenciamento, os protocolos e a rede de preservadores ainda não estão em operação.

## Licença

O código do Preservador é disponibilizado sob a [GNU Affero General Public License v3.0](LICENSE) (AGPLv3).
