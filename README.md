\documentclass[10pt,a4paper]{article}
\usepackage[utf8]{inputenc}
\usepackage[margin=0.5in]{geometry}
\usepackage{enumitem}
\usepackage{titlesec}
\usepackage{xcolor}
\usepackage{hyperref}
\usepackage{fontawesome5}
\usepackage{tabularx}
\usepackage{array}

\definecolor{headercolor}{RGB}{51, 51, 51}
\definecolor{subtitlecolor}{RGB}{102, 102, 102}
\definecolor{accentcolor}{RGB}{0, 102, 204}
\definecolor{lightgray}{RGB}{245, 245, 245}

\hypersetup{colorlinks=true, linkcolor=accentcolor, urlcolor=accentcolor}

\pagestyle{empty}
\setlength{\parindent}{0pt}
\setlist[itemize]{leftmargin=*, nosep, itemsep=1.2pt, label=\textbullet}

\titleformat{\section}{\large\bfseries\centering}{}{0em}{}[\titlerule]
\titlespacing*{\section}{0pt}{7pt}{4pt}

\newcommand{\experienceheader}[4]{
    \textbf{\color{subtitlecolor}#1} \hfill #2\\
    \textbf{#3} \hfill \textit{#4}\\
}

\newcommand{\achievementbox}[3]{
    \begin{minipage}[t]{0.3\textwidth}
        \centering
        \colorbox{lightgray}{\makebox[0.9\textwidth][c]{
            \begin{minipage}{0.85\textwidth}
                \centering
                \vspace{3pt}
                #1\ \textbf{\footnotesize #2}\\[1pt]
                {\footnotesize #3}
                \vspace{3pt}
            \end{minipage}
        }}
    \end{minipage}
}

\begin{document}

\begin{center}
    {\LARGE\bfseries\color{headercolor} Guilherme Lopes Resende}\\[3pt]
    {\large\color{subtitlecolor} AI Engineer | RAG | LLM Systems | LangChain | LangGraph | Python | Production AI Workflows}\\[4pt]
    {\footnotesize
    (22) 98101-3061 \quad • \quad guilhermelr291dev@gmail.com \quad • \quad
    \href{https://github.com/guilhermelr291}{GitHub} \quad • \quad
    \href{https://linkedin.com/in/guilherme-resende-78b258258}{LinkedIn} \quad • \quad
    Nova Friburgo, Brazil}
\end{center}

\section{Professional Summary}
{\footnotesize
AI Engineer building \textbf{production-grade LLM-powered workflows} and \textbf{RAG systems from zero to production}.
Hands-on experience with \textbf{agentic pipeline design}, retrieval engineering, prompt engineering, evaluation-oriented iteration, \textbf{AI framework migrations} and AI-enabled business workflows connected to real operational data.
Strong focus on \textbf{observability}, monitoring, incident diagnosis, and
\textbf{cost-aware AI implementation}, leveraging techniques such as fine-tuned
small models, optimized retrieval pipelines and lightweight LLM filters.
Solid full-stack engineering background in \textbf{Python}, \textbf{Node.js}, \textbf{TypeScript}, \textbf{React}, and modern architectures (Clean Architecture, DDD), providing strong ownership across the entire product stack when needed.
Experienced leading squads, making architecture decisions, and working cross-functionally with clients and product owners to deliver reliable, production-grade systems.
}

\section{Core Skills}
\vspace{2pt}
\noindent{\footnotesize
\textbf{AI / RAG / LLM Systems:} LangChain, LangGraph, agentic pipeline design, end-to-end RAG, tool-based flows, reranking, prompt engineering, evaluation-oriented iteration, cost-aware implementation\\
\textbf{Observability / AI Ops:} monitoring, data quality checks, incident diagnosis, observability for agentic workflows, operational feedback loops, answer reliability improvement\\
\textbf{Backend / APIs:} Python, Node.js (Express, Fastify), FastAPI, REST APIs, JWT, OAuth, API versioning, webhooks, TypeScript, JavaScript\\
\textbf{Architecture:} Clean Architecture, DDD, MVC, Hexagonal Architecture, SOLID\\
\textbf{Databases:} PostgreSQL, MySQL, MongoDB\\
\textbf{Infrastructure / DevOps:} Docker, CI/CD with GitHub Actions\\
\textbf{Frontend:} React, Next.js, Tailwind CSS, TanStack Query, Zustand\\
\textbf{Other:} Automated testing (Vitest, Jest), RabbitMQ, Selenium and Playwright (RPA)
}

\section{Key Achievements}
\vspace{2pt}
\noindent
\achievementbox{\faRobot}{RAG in Production}{Built end-to-end \textbf{production RAG
solutions} mainly in the \textbf{legal field}, combining \textbf{RAG} for unstructured
documents with \textbf{tool-based approaches} for structured data sources.}
\hfill
\achievementbox{\faExchangeAlt}{Stack Migrations}{Identified inadequate technologies holding the team back and led \textbf{framework migrations} for a more deterministic, parallelism-friendly approach suited to production needs.}
\hfill
\achievementbox{\faCloud}{Scale \& Efficiency}{Reduced AI costs by up to \textbf{30\%} using \textbf{fine-tuned small models} per task; designed retrieval strategies balancing \textbf{precision, recall, and cost},
combining multiple techniques to keep quality high without relying on large models.}

\section{Experience}
\vspace{2pt}
\experienceheader{Rachel AI}{London (Remote)}{Full Stack Developer / AI Engineer}{Nov 2025 -- Present}
\textbf{\footnotesize Full-time}
\begin{itemize}
    \item {\footnotesize Designed, maintained, and evolved the entire \textbf{agentic pipeline} with a precise \textbf{RAG} and \textbf{tool-based flow} capable of handling both structured and unstructured documents in the \textbf{legal field}.}
    \item {\footnotesize Led the \textbf{migration of the full AI framework} to a more deterministic, parallelism-friendly, and production-suitable approach, replacing an inadequate prior stack that was holding the team back.}
    \item {\footnotesize Made critical \textbf{architecture decisions} to keep the MVP lean, including infrastructure delegation and framework choices aligned with long-term maintainability.}
    \item {\footnotesize Drove continuous improvement in the \textbf{RAG workflow} through different retrieval strategies, model evaluations, and \textbf{human and AI feedback} loops.}
    \item {\footnotesize Reduced AI costs by up to \textbf{30\%} by replacing large general-purpose models with \textbf{smaller specialized models} fine-tuned for specific tasks.}
    \item {\footnotesize Designed \textbf{retrieval strategies} balancing precision, recall, and cost, combining multiple complementary techniques to maintain answer quality without relying on expensive models.}
    \item {\footnotesize Implemented \textbf{monitoring and data quality checks} for both the agentic workflow and the broader application.}
    \item {\footnotesize Continuously refined prompts, retrieval behavior, and failure handling based on operational feedback to increase \textbf{answer reliability in production}.}
\end{itemize}

\vspace{2pt}
\experienceheader{Rime Tecnologia}{S\~{a}o Paulo (Remote)}{Full Stack Web Developer}{Nov 2024 -- Nov 2025}
\textbf{\footnotesize Full-time}
\begin{itemize}
    \item {\footnotesize Delivered \textbf{3+ complete products from scratch} --- frontend, backend, infrastructure, and deployment --- in a fast-paced software house environment with multiple simultaneous demands.}
    \item {\footnotesize Led \textbf{architecture decisions} (MVC, Clean Architecture, DDD) and code standardization across Node.js, React, and Python projects.}
    \item {\footnotesize Maintained full \textbf{VPS infrastructure} with Docker, Nginx, and CI/CD via GitHub Actions; acted as \textbf{technical reference} and led small development squads.}
    \item {\footnotesize Worked directly with clients and POs for requirements gathering, technical alignment, and roadmap definition.}
\end{itemize}

\vspace{2pt}
\experienceheader{Go Live Tech}{Niter\'{o}i (Remote)}{RPA Consultant}{Dec 2022 -- Nov 2024}
\textbf{\footnotesize Full-time}
\begin{itemize}
    \item {\footnotesize For approximately one year, was the \textbf{sole developer} working on a large and complex project for the company's \textbf{first international client}.}
    \item {\footnotesize Responsible for development and direct communication with the client, identifying needs, making corrections and adaptations when necessary, and implementing new features.}
    \item {\footnotesize Responsible for the support of one of the company's most scaled and important automations.}
    \item {\footnotesize Received \textbf{internal performance awards}, voted by the team (listed on LinkedIn).}
\end{itemize}

\section{Activities}
\vspace{2pt}
\noindent{\footnotesize
Participant in \textbf{BASE}, a mentoring group by Yuri Pereira, founder of BorderlessCoding, focused on promoting developer connections and developing hard and soft skills.
}

\section{Education}
\vspace{2pt}
\noindent\textbf{\footnotesize CEFET/RJ --- Federal Center for Technological Education, Nova Friburgo} \hfill {\footnotesize Graduated Sep 2025}\\
{\footnotesize B.S. in Information Systems}

\section{Languages}
\vspace{2pt}
\begin{center}
{\footnotesize \textbf{Portuguese} --- Native \quad\quad \textbf{English} --- C1 Advanced \quad (\href{https://cert.efset.org/kXqBK2}{EF SET Certificate})}
\end{center}

\end{document}
