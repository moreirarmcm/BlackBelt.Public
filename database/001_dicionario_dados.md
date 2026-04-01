# Dicionário de Dados

# 1. Cadastro

## cadastro.Pessoa
	Armazena os dados pessoais do usuário. 

## cadastro.Aluno
	Armazena dados relativos à matrícula do usuário em uma filial. 
	
## cadastro.Contato
	Armazena os dados de contato e endereço do usuário.

## cadastro.Academia
	Funciona como uma entidade superior de filiais. 

## cadastro.Responsavel
	Armazena os dados do responsável vinculado ao aluno.

## cadastro.Filial
	Unidade física/operacional da academia.

## cadastro.Titulo
	Armazena os títulos possíveis da academia.

## cadastro.AlunoTitulo
	Armazena o histórico de títulos atribuídos a um aluno.

# 2. Atividade

## atividade.Disciplina
	Armazena a disciplina base do domínio de atividade.

## atividade.Modalidade
	Armazena as modalidades associadas a uma disciplina.

## atividade.FilialModalidade
	Armazena a oferta de uma modalidade em uma filial.

## atividade.AlunoFilialModalidade
	Armazena o vínculo do aluno com uma modalidade ofertada por uma filial.

## atividade.Aula
	Armazena as aulas criadas para uma determinada modalidade ofertada em uma filial.

## atividade.AlunoAula
	Armazena o vínculo entre aluno e aula.

# 3. Segurança

## seguranca.Usuario
	Armazena os dados de autenticação e acesso do usuário do sistema.

## seguranca.Perfil
	Armazena os perfis de acesso do sistema.

## seguranca.UsuarioPerfil
	Armazena o vínculo entre usuário e perfil.

# 4. Solicitações

## solicitacoes.SolicitacaoInscricao
	Armazena a solicitação formal de inscrição no sistema.

