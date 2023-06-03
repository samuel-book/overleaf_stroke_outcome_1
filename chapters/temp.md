\subsection{Pre-stroke mRS distribution (full recovery from current stroke)}

The pre-stroke mRS distribution (equivalent to full recovery from the current stroke) is taken from the SSNAP dataset, which contains a record of mRS prior to the current stroke, extracting the patients that have an ischaemic stroke and using NIHSS 0-10 as a surrogate for nLVO, or NIHSS 11+ as a surrogate for LVO. These mRS distributions are then corrected for the excess deaths due to treatment (see below).

\subsection{mRS distribution for time when treatment has no effect}

For nLVO patients the \textit{no effect mRS distribution} is taken from the untreated control group of combined nLVO/LVO data from Lees et al. \cite{lees_time_2010}, and from that we remove the contribution of the LVO patients by using the results from the untreated control group of LVO-only data from Goyal et al. \cite{goyal_endovascular_2016} . Each mRS distribution (Lees, and Goyal) are adjusted to account for the excess deaths due to IVT treatment (using their relevant patient type: nLVO and/or LVO, see \textit{weights} subsection below for more information). The two mRS distributions are then combined, using weightings (154\% Lees and -54\% Goyal) chosen such that the resulting mRS distribution represents just the nLVO patients and matches the P(mRS $\leq$ 1, t = No Effect) of 0.46 (from the control group in Emberson with NIHSS of 0-10).

The weights used to combine these two mRS distributions (61\% fully recovered & 39\% no effect) were informed by data from Emberson et al. 2014, and found in order to match the P(mRS *\leq* 1, \textit{t = 0}) of 0.63 (which was derived from extrapolating odds of good outcome back to \textit{t = 0}. 

For LVO patients the \textit{no effect} mRS distribution is taken from the untreated control population from Goyal et al. \cite{goyal_endovascular_2016}. This mRS distribution is then corrected for the excess deaths due to treatment.




(this data is obtained from Sentinel Stroke National Audit Programme, SSNAP, using 246,676 emergency stroke admissions to acute stroke teams in England and Wales between 2016 and 2018)