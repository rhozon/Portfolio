# Portfolio
Repositório de portfolio e currículo

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
% Beamer Presentation
% LaTeX Template
% Version 1.0 (10/11/12)
%
% This template has been downloaded from:
% http://www.LaTeXTemplates.com
%
% License:
% CC BY-NC-SA 3.0 (http://creativecommons.org/licenses/by-nc-sa/3.0/)
%
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

%----------------------------------------------------------------------------------------
%   PACKAGES AND THEMES
%----------------------------------------------------------------------------------------

\documentclass{beamer}

\mode<presentation> {

%dencoding
%--------------------------------------
\usepackage[utf8]{inputenc}
\usepackage[T1]{fontenc}
%--------------------------------------
\usepackage{graphicx}
%Portuguese-specific commands
%--------------------------------------
\usepackage[portuguese]{babel}
%--------------------------------------

%Hyphenation rules
%--------------------------------------
\usepackage{hyphenat}
\hyphenation{mate-mática recu-perar}
%--------------------------------------

%--------------------------------------
\usepackage{textpos}
%--------------------------------------
\fboxsep0pt
%--------------------------------------

% --verticalmente centralizado----
\usepackage{array,booktabs}% http://ctan.org/pkg/{array,booktabs}
% ---------------


\bibliographystyle{plain}

% The Beamer class comes with a number of default slide themes
% which change the colors and layouts of slides. Below this is a list
% of all the themes, uncomment each in turn to see what they look like.

%\usetheme{default}
%\usetheme{AnnArbor}
%\usetheme{Antibes}
%\usetheme{Bergen}
%\usetheme{Berkeley}
%\usetheme{Berlin}
%\usetheme{Boadilla}
%\usetheme{CambridgeUS}
%\usetheme{Copenhagen}
%\usetheme{Darmstadt}
%\usetheme{Dresden}
%\usetheme{Frankfurt}
%\usetheme{Goettingen}
%\usetheme{Hannover}
%\usetheme{Ilmenau}
%\usetheme{JuanLesPins}
%\usetheme{Luebeck}
%\usetheme{Madrid}
%\usetheme{Malmoe}
%\usetheme{Marburg}
\usetheme{Montpellier}
%\usetheme{PaloAlto}
%\usetheme{Pittsburgh}
%\usetheme{Rochester}
%\usetheme{Singapore}
%\usetheme{Szeged}
%\usetheme{Warsaw}


% As well as themes, the Beamer class has a number of color themes
% for any slide theme. Uncomment each of these in turn to see how it
% changes the colors of your current slide theme.

%\usecolortheme{albatross}
%\usecolortheme{beaver}
%\usecolortheme{beetle}
%\usecolortheme{crane}
\usecolortheme{dolphin}
%\usecolortheme{dove}
%\usecolortheme{fly}
%\usecolortheme{lily}
%\usecolortheme{orchid}
%\usecolortheme{rose}
%\usecolortheme{seagull}
%\usecolortheme{seahorse}
%\usecolortheme{whale}
%\usecolortheme{wolverine}

%\setbeamertemplate{footline} % To remove the footer line in all slides uncomment this line
\setbeamertemplate{footline} % To replace the footer line in all slides with a simple slide count uncomment this line

\setbeamertemplate{footline}{
\leavevmode%
  \hbox{%
  \begin{beamercolorbox}[wd=.4\paperwidth,ht=2.25ex,dp=1ex,center]{author in head/foot}%
    \usebeamerfont{author in head/foot}\insertshortauthor
  \end{beamercolorbox}%
  \begin{beamercolorbox}[wd=.6\paperwidth,ht=2.25ex,dp=1ex,center]{title in head/foot}%
    \usebeamerfont{title in head/foot}\insertshorttitle\hspace*{6em}
    \insertframenumber{} / \inserttotalframenumber\hspace*{1ex}
  \end{beamercolorbox}}%
  \vskip0pt
}

%\setbeamertemplate{navigation symbols}{} % To remove the navigation symbols from the bottom of all slides uncomment this line
}

\usepackage{graphicx} % Allows including images
\usepackage{booktabs} % Allows the use of \toprule, \midrule and \bottomrule in tables

% letras riscadas em cima
\usepackage[normalem]{ulem}
\usepackage[colorlinks]{hyperref}
% -----------------------------------------------------
% descomente essa seção para habilitar o logo da utfpr
% (talvez o tamanho e o local devem ser alterados para
% caber no cabeçalho)
%
% \addtobeamertemplate{frametitle}{}{%
% \begin{textblock*}{100mm}(0.85\textwidth,-1.9cm)
% \includegraphics[height=.1\textwidth]{./imagens/utfpr-logo.png}
% \end{textblock*}
% }
% -----------------------------------------------------

%%----------------------------------------------------------------------------------------
%   TITLE PAGE
%----------------------------------------------------------------------------------------

%cores
%--------------------------------------
\newcommand{\azul}[1]{\textcolor{blue}{#1}}

\newcommand{\vermelho}[1]{\textcolor{red}{#1}}

\newcommand{\verde}[1]{\textcolor{green}{#1}}

\newcommand{\preto}[1]{\textcolor{black}{#1}}

\setbeamertemplate{background}{\tikz[overlay,remember picture]\node[opacity=0.4]at (current page.center){\includegraphics[width=2cm]{me(1)}};}


\usepackage{tikz}
\usepackage{kantlipsum}
%--------------------------------------
\title[Apresentação do Portfólio]{Portfólio} % The short title appears at the bottom of every slide, the full title is only on the title page




\author[Rodrigo Hermont Ozon]{
Rodrigo Hermont Ozon\\
} % Your name

\institute[UTFPR] % Your institution as it will appear on the bottom of every slide, may be shorthand to save space
{
Histórico de Entregas e Conquistas\\ % Your institution for the title page


\medskip

\textcolor{blue}{\url{https://www.linkedin.com/in/rodrigohermontozon}}

\vspace{.25cm}
\textcolor{blue}{\url{http://lattes.cnpq.br/3532649625879285}
}}

\date{\today} % Date, can be changed to a custom date

% numerais romanos
\makeatletter
\newcommand*{\rom}[1]{\expandafter\@slowromancap\romannumeral #1@}
\makeatother
\begin{document}

\begin{frame}
\titlepage % Print the title page as the first slide
\end{frame}

\newcommand{\sumario}{
\begin{frame}[allowframebreaks]{Outline}
\frametitle{Sumário} % Table of contents slide, comment this block out to remove it
\tableofcontents % Throughout your presentation, if you choose to use \section{} and \subsection{} commands, these will automatically be printed on this slide as an overview of your presentation
\end{frame}
}

\sumario

%----------------------------------------------------------------------------------------
%   PRESENTATION SLIDES
%-----------------------------------------------------------\
\section{Apresentação Pessoal}
\begin{frame}
\frametitle{Apresentação pessoal}

\centering
\includegraphics[widht=2.5cm,height=2.5cm]{imagens/me.jpg}

\footnotesize
\begin{flushleft}

   \textit{Rodrigo Hermont Ozon, 36 anos, economista, ocupei os seguintes cargos}: 
   \begin{itemize}
       \item \textit{Data Scientist}
       \item Coordenador de Projetos, Captação de Recursos
       \item Pesquisador e Professor
       \item Consultoria Econômica
   \end{itemize}

   
\end{flushleft}
    
\end{frame}

%------------------------------------------------
\subsection{Resumo dos serviços prestados}

\begin{frame}
\frametitle{Resumo dos serviços prestados}

Já trabalhei nas seguintes áreas: 
\begin{itemize}
    \item Mercado Financeiro
    \item Pesquisa científica
    \item Terceiro Setor 
    \item Indústria 
    \item Tecnologia (\textit{start up})
    \item Professor universitário
\end{itemize}

\end{frame}
%------------------------------------------------

%------------------------------------------------
\begin{frame}
\frametitle{Resumo dos serviços prestados}

\footnotesize
Como \textit{Data Scientist}:


\begin{itemize}
    \item<1-3> Construção de indicadores de perfomance (KPIs), indicadores de risco (KRIs), relatórios gerenciais dinâmicos em tempo real.
    \item<2-3> Construção de \textit{dashboard} de visualização em tempo real (\textit{Business Intelligence}) de dados financeiros (ativos financeiros) e informações contábeis para a alta gestão 
    \item<2-3> Visualização de dados estatísticos da economia paranaense (visão de cadeias produtivas industriais)
    \item<3-3> Construção de Índice de Desenvolvimento Empresarial com base em dados secundários da economia;
\end{itemize}

\end{frame}

%------------------------------------------------
\begin{frame}
\frametitle{Resumo dos serviços prestados}

\footnotesize
Como coordenador de projetos:
\begin{itemize}
\item Captação de recurso para execução do projeto 
\item Submissão, planejamento e reprogramação de plano de projetos
\item Fui avaliador dos projetos que as empresas submetiam ao edital Senai/Sesi de Inovação. Também fui avaliador no PAPPE/Subvenção parceria IBQP/Sebrae
\item Professor de pós-graduação na FESP no MBA em Gerenciamento de Projetos na disciplina de Gerenciamento de Integração de Projetos metodologia PmBok/PMI
\end{itemize}

\end{frame}
%------------------------------------------------
\begin{frame}
\frametitle{Resumo dos serviços prestados}


Como pesquisador, professor e consultor:

\footnotesize
\begin{itemize}
    \item Fui pesquisador bolsista da Fundação Araucária e FIEP sobre cadeias produtivas industriais paranaenses, isso me deu \textit{know how} para trabalhar com estudos/pesquisa de mercado de alto nível quando fiz mestrado em desenvolvimento econômico
    
    \item Fui professor das disciplinas na graduação: Mercados Financeiros, Economia Monetária e Financeira, Métodos Quantitativos, Controle Estatístico de Processos, Administração Financeira, Indicadores de Desempenho da Indústria.  
    
    \item Como consultor viajei os estados brasileiros contribuindo para a implantação e melhoria do projeto ID-MPE (mais detalhes a seguir \textcolor{blue}{\ref{idmpe}}) para os Sebraes UF. Também faço consultoria econômica para empresas e pessoas físicas com planos de investimentos;
\end{itemize}

\end{frame}
%------------------------------------------------------------
\section{Entregas: Projetos e trabalhos feitos por onde atuei}
\begin{frame}
\frametitle{Projetos e trabalhos feitos}

Consulte meus projetos que estão disponíveis na \textit{web}:

Como \textit{Data Scientist}:
\small
\begin{itemize}
    \item<1-4> \textcolor{blue}{\href{http://www.leg.ufpr.br/doku.php/projetos:ehlers:volprev}{Modelagem de Volatilidade em Séries Financeiras (Laboratório de Estatística e Geoinformação/UFPR)}} 
    
    \item<2-4> \textcolor{blue}{\href{https://rhoportolio.blogspot.com/2019/09/salarios-de-admissao-por-cargo.html}{Estudo de Mercado para parametrização salarial para contratação de profissionais}} 
    
    \item<2-4> \textcolor{blue}{\href{http://sites.pr.sebrae.com.br/leigeral/wp-content/uploads/sites/35/2014/02/Cartilha_IDMPE_PR_-_junho_2011.pdf}{Índice de Desenvolvimento Municipal das Micro e Pequenas Empresas (SEBRAE/IBQP)}}\label{idmpe}
    \item<3-4> \textcolor{blue}{\href{http://sites.pr.sebrae.com.br/leigeral/wp-content/uploads/sites/35/2014/09/IDME_2013_web.pdf}{IDMPE (2012)}}
\end{itemize}


\end{frame}
%------------------------------------------------------------
\begin{frame}
\frametitle{Projetos e trabalhos feitos}

\footnotesize
Dos projetos que coordenei e executei e não estão disponíveis na \textit{web} destaco:
\begin{itemize}
    \item No Grupo Bitcoin Banco: Análise e Indicadores de Risco (área de atendimento para GBB), Automação dos relatórios de desempenho gerencial da área de atendimento do GBB, Indicador de Desempenho e Performance da Área de Atendimento GBB, Relatório \textit{realtime} dos dados do \textit{e-commerce} Get4Bit, Visualização de Dados do Setor de Compras do GBB (\href{https://www.linkedin.com/in/rodrigohermontozon/}{\textcolor{blue}{vide perfil no meu Linkedin)}}
    \item Na FIEP: Fiz análises setoriais de cadeias produtivas industriais paranaenses, contribui para a \textcolor{blue}{\href{http://www.fiepr.org.br/para-empresas/estudos-economicos/sondagem-industrial-1-20654-238938.shtml}{Pesquisa de Sondagem Industrial}} e apoiei as negociações coletivas salariais de alguns sindicatos filiados. Também fiz captação de recursos submetendo projetos a instituições de financiamento como Banco do Brasil, FINEP, PNUD/ONu etc.
    \item No \textcolor{blue}{\href{http://ibqp.org.br/}{IBQP}} além do IDMPE fui voluntário/avaliador do \textcolor{blue}{\href{http://www.ibqp.org.br/projetos/movimento-parana-competitivo/sobre-mpc/}{Movimento Paraná Competitivo}} da \textcolor{blue}{\href{http://www.fnq.org.br/}{}Fundação Nacional da Qualidade}} 
\end{itemize}



\end{frame}
%-------------------------------------------------
\begin{frame}
\frametitle{Perfis Públicos}

Acesse minhas publicações (visualizações de dados e linhas de códigos) nos seguintes endereços:

\small
\begin{itemize}
    \item No GitHub: \textcolor{blue}{\href{https://github.com/rhozon}{https://github.com/rhozon}}
    \item Na galeria do Tableau Public: \textcolor{blue}{\href{https://public.tableau.com/profile/rodrigo.h.ozon#!/}{https://public.tableau.com/profile/rodrigo.h.ozon#!/}}
    \item Protótipo de visualização de dados para a FIEP: \textcolor{blue}{\href{http://fiepdesenvolvimento.blogspot.com/}{http://fiepdesenvolvimento.blogspot.com/}}
\end{itemize}

\end{frame}
%------------------------------------------------------------




%------------------------------------------------
\begin{frame}
\frametitle{Contato}

\textit{\textcolor{blue}{\href{https://api.whatsapp.com/send?phone=5541988382904&text=Ol\%C3\%A1\%20Rodrigo\%2C\%20vi\%20seu\%20portf\%C3\%B3lio\%20no\%20linkedin\%2C\%20tenho\%20interesse\%20em\%20conhecer\%20um\%20pouco\%20mais\%20do\%20seu\%20trabalho.\%20Podemos\%20conversar\%20a\%20respeito\%20\%3F}{Me adicione no whatsapp}}} \small{+55 41 98838-2904}

\vspace{.5cm}
Endereço de e-mail: \textit{\textcolor{blue}{\href{mailto:rodrigoozon@yahoo.com.br}{rodrigoozon@yahoo.com.br}}} \\ % Your email address



\end{frame}

%----------------------------------------
%\section{Referências}

%\begin{frame}[allowframebreaks]{Outline}
%\frametitle{Referências}
%\bibliography{referencias}
%\end{frame}

%------------------------------------------------


%----------------------------------------------------------------------------------------
\end{document}
