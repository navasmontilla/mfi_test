## Prueba de latex

Mediante el Tercer Teorema del Transporte de Reynolds podemos escribir la \textbf{ecuación de conservación de la masa} para el volumen de control (VC) fijo de 


\begin{equation}\label{eq:eqmasa}
    \underbrace{\frac{d}{dt}\int_{VC} \rho dV}_{I} +  \underbrace{\int_{SC} \rho(\vec{\mathbf{v}}- \vec{\mathbf{v}}_c )\cdot \hat{\mathbf{n}}dS}_{II}=0
\end{equation}



Agrupando los términos anteriores ($I+II=0$) se obtiene la ecuación de conservación de la masa para este VC particular

\begin{equation}\label{eq:eqmasa2}
   ( \rho Q)_1=(\rho Q)_2
\end{equation}
y como $\rho$ es constante (flujo incompresible) se reduce a

\begin{equation}\label{eq:eqmasa3}
   Q\equiv \hbox{const.}
\end{equation}


\begin{equation}\label{eq:emec}
\boxed{
    \textcolor[RGB]{0, 152, 46}{ \rho Q \left[ \left( \frac{v^2}{2}+\frac{p}{\rho}+gz  \right)_2  - \left( \frac{v^2}{2}+\frac{p}{\rho}+gz  \right)_1 \right] } = \textcolor[RGB]{0, 0, 255}{ \dot{W}_{a\rightarrow f} } - \textcolor[RGB]{255, 100, 0}{\int_{VC} \Phi_v  dV}
     }
\end{equation}


\begin{table}[!h]
\centering
\begin{tabular}{c|c|c|c|c}
\multicolumn{2}{c}{}  & \multicolumn{3}{c}{Fuentes de energía} \\\cline{3-5} 
Ecuación &Energía específica        &      Calor            &  Impulsión & Disipación \\ \hline
\textit{Interna} & \textcolor[RGB]{0, 152, 46}{$e$} &   \textcolor[RGB]{255, 0, 0}{$\dot{\mathcal{Q}}$}  &   0        &  \textcolor[RGB]{255, 100, 0}{$\int_{VC} \Phi_v  dV$}     \\
\textit{Mecánica} &  \textcolor[RGB]{0, 152, 46}{$\frac{v^2}{2}+\frac{p}{\rho}+gz$} &  0  &     \textcolor[RGB]{0, 0, 255}{$\dot{W}_{a\rightarrow f}$}        & \textcolor[RGB]{255, 100, 0}{$- \int_{VC} \Phi_v  dV$}     \\\hline
\textit{Total} &   \textcolor[RGB]{0, 152, 46}{$e+\frac{v^2}{2}+\frac{p}{\rho}+gz$} &    \textcolor[RGB]{255, 0, 0}{$\dot{\mathcal{Q}}$}  &   \textcolor[RGB]{0, 0, 255}{$\dot{W}_{a\rightarrow f}$}        &  0     \\
\end{tabular}
\caption{Balances de energía en el VC para las distintas formas de energía.}
\label{tab:energias}
\end{table}
