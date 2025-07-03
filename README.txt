# 🛡️ Projeto de Hardening de Rede – Organização de Mídia Social

Este projeto foi desenvolvido como parte de uma atividade prática do curso de Cibersegurança. O objetivo é analisar uma violação de dados e aplicar ferramentas e métodos de **hardening de rede** para proteger a organização contra futuros ataques.

## 🧩 Cenário

A organização sofreu uma **grande violação de dados**, expondo informações sensíveis de usuários (nome, endereço, etc.). Após investigação, foram identificadas **4 vulnerabilidades críticas**:

- Compartilhamento de senhas entre funcionários.
- Uso de senha padrão para o administrador do banco de dados.
- Firewalls sem regras configuradas.
- Ausência de autenticação multifatorial (MFA).

---

## 🔐 Ferramentas e Métodos Implementados

### ✅ 1. Autenticação Multifatorial (MFA)
- Implementação de MFA para acessos críticos.
- Protege contra acessos não autorizados, mesmo com senha comprometida.

### ✅ 2. Regras de Firewall + Filtragem de Portas
- Configuração de regras de entrada/saída.
- Bloqueio de portas desnecessárias e protocolos perigosos.
- Prevenção de tráfego malicioso.

### ✅ 3. Políticas de Senha Fortes
- Senhas únicas e complexas (conforme NIST).
- Proibição de senhas padrão e compartilhamento.
- Adoção de gerenciadores de senhas corporativos.

---

## 💡 Recomendações e Justificativas

### 🔒 MFA
- **Por que?** Evita invasões com credenciais roubadas.
- **Frequência:** Configuração única + manutenção periódica.

### 🔥 Firewall + Port Filtering
- **Por que?** Controla tráfego e bloqueia ataques externos.
- **Frequência:** Regras revisadas mensalmente ou após incidentes.

---

## 🎯 Resultados Esperados

- Redução do risco de violação de dados.
- Maior controle sobre acessos e tráfego de rede.
- Adoção de uma postura proativa e auditável de segurança.

---

## 🧰 Tecnologias Utilizadas

- 🔑 Google Authenticator / Microsoft Authenticator (MFA)
- 🔥 Firewalls NGFW com filtragem de portas
- 🔐 Bitwarden / LastPass Enterprise (gerenciador de senhas)
- 📊 SIEM (análise de logs)

---

## 📎 Autor

**Tiago Sants**  
🔗 [LinkedIn](https://www.linkedin.com/in/tiago-sants-295a1565)  
🐙 [GitHub](https://github.com/tiagosaants)  
📩 sanguec@live.com  
📱 +55 11 98222-8822

---

> Projeto desenvolvido como parte do Certificado Profissional de Cibersegurança do Google.

