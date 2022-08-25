# Técnica de validação cruzada estratificada e seleção de hiperparâmetros com Randon Search

## Sobre a base:

Conjunto de dados de pacientes hepáticos indianos Este conjunto de dados contém 416 registros de pacientes hepáticos e 167 registros de pacientes não hepáticos. O conjunto de dados foi coletado no nordeste de Andhra Pradesh, Índia. O rótulo da classe divide os pacientes em 2 grupos (doente hepático ou não). Este conjunto de dados contém 441 registros de pacientes do sexo masculino e 142 registros de pacientes do sexo feminino.

Informações dos atributos

V1. Idade do paciente. Qualquer paciente cuja idade ultrapasse 89 anos é listado como tendo idade "90".
V2. Sexo do paciente
V2. Sexo do paciente
V3. Bilirrubina Total
V4. Bilirrubina Direta
V5. Alkphos Fosfatase Alcalina
V6. Sgpt Alanina Aminotransferase
V7. Sgot Aspartato Aminotransferase
V8. Proteínas Totais
V9. Albumina
V10. Relação A/G Albumina e Relação Globulina

Fonte: https://www.openml.org/search?type=data&sort=runs&id=1480&status=active

## Objetivo do desafio:

**Aplicação nos modelos SVM e Randon Forest, técnica de validação de dados para a diminuição de viés (abordagem simples cross validation) e aplicação de Random Search para uma melhor sintonia dos hiperparâmetros dos modelos, utilizando como métrica o F-score.**
