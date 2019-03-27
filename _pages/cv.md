---
layout: archive
title: "Resume"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}
%!TEX TS-program = xelatex
%!TEX encoding = UTF-8 Unicode
% Awesome CV LaTeX Template
%
% This template has been downloaded from:
% https://github.com/posquit0/Awesome-CV
%
% Author:
% Claud D. Park <posquit0.bj@gmail.com>
% http://www.posquit0.com
%
% Template license:
% CC BY-SA 4.0 (https://creativecommons.org/licenses/by-sa/4.0/)
% 	TO DO:
%	- DEVELOP A 1 page version with only relevant stuff. 


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     Configuration
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%%% Themes: Awesome-CV
\documentclass[]{awesome-cv}
\usepackage{textcomp}
%%% Override a directory location for fonts(default: 'fonts/')
\fontdir[fonts/]

%%% Configure a directory location for sections
\newcommand*{\sectiondir}{resume/}

%%% Override color
% Awesome Colors: awesome-emerald, awesome-skyblue, awesome-red, awesome-pink, awesome-orange
%                 awesome-nephritis, awesome-concrete, awesome-darknight
%% Color for highlight
% Define your custom color if you don't like awesome colors
\colorlet{awesome}{awesome-red}
%\definecolor{awesome}{HTML}{CA63A8}
%% Colors for text
%\definecolor{darktext}{HTML}{414141}
%\definecolor{text}{HTML}{414141}
%\definecolor{graytext}{HTML}{414141}
%\definecolor{lighttext}{HTML}{414141}

%%% Override a separator for social informations in header(default: ' | ')
%\headersocialsep[\quad\textbar\quad]
    \begin{document}

%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     Profile
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\begin{center}
	\headerfirstnamestyle{Abdulrahman} \headerlastnamestyle{Alkurdi} \\
	\vspace{2mm}
	{\faEnvelope\ alkurdi2@illinois.edu} | {\faMobile\ (217) 979-7913} | {\faMapMarker\ Urbana, IL} | {\faLink\ www.linkedin.com/in/abdulalkurdi}
\end{center}
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     Education
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\cvsection{Education}
\begin{cventries}
	\cventry
	{Doctorate in Aerospace Engineering}
	{University of Illinois at Urbana Champaign}
	{May 2021}
	{3.3/4}
	{ Area of interest:  Machine Learning (RL, ML, DL and vision), Autonomy, Robotics \& UAVs, Decision and Control, Applied problems. 
	\vspace{5mm}
	\begin{cvitems}
		\item {\textbf{Classes}: Reinforcement Learning, Machine Learning, Autonomous Vehicle Systems, Autonomous Decision Making, and Controls.}
		%\item{\textbf{Activities:} Undergrad mentoring, Saudi Students Ass., Bass Fishing club. Ask me where my best fishing spots are, I might just tell you.}
		\item{Awarded KACST PhD fellowship. (2016-current)}
	\end{cvitems}
	}
	\cventry
	{Bachelors \& Masters in Mechanical Engineering}
	{Lehigh University}
	{Jan 2011}
	{3.3/4}
	{Focused on tech and product development, entrepreneurship and manufacturing to bring new skill sets and talents to job market. \newline
	\vspace{5mm}
	\begin{cvitems}
		%\item{\textbf{Memberships}: Bikers Club, Diving Club, South Bethlehem Boxing Club, Sailing Club, and Esplanaders Debate Society.}
		\item'{Awarded SABIC College Scholarship (0.4\% acceptance rate across Saudi Arabia) and became mentor to future scholars (2009-2016).}
	\end{cvitems}
	}
\end{cventries}


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     Projects
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\vspace{-4mm}
\cvsection{Experience \& Projects}
\begin{cventries}
	
	\cventry
	{Research Specialist at KACST and Stanford University}
	{Stall/Spin Detection in Unmanned Aircraft}
	{Palo Alto \& Riyadh}
	{Jan 2015 – Aug 2016}
	{\vspace{1mm}
	\begin{cvitems}
		\item {Designed, built subscale aircraft to conducted experimental stall \& spin research by flowfield visualization and characterization.}
		\item {Programmed DAQ to log structured data for fusion and autopilot detection in C++.}
		\item {Perform ground testing for sensors, aircraft and electronics pre-flight.}
		\item {Extracted unbiased measurements for aerodynamic state estimation leading to stall detection, prediction and recovery algorithm.}
		\item {Published and presented work in a peer reviewed conference.}
		\item {\textbf{Publication:} Bunge, R.A., Alkurdi, A.E., Alfaris, E. and Kroo, I., 2016. In-Flight Measurement of Wing Surface Pressures on a Small-Scale UAV During Stall/Spin Maneuvers. \textit{ AIAA Flight Testing Conference} (p. 3652)}
	\end{cvitems}}

	\vspace{-3mm}
	\cventry
	{}
	{Learning to Fly a Glider Using RL}
	{Champaign, IL}
	{}
	{\vspace{-4mm}
	\begin{cvitems}
		\item {Coded a reduced order flight and thermals simulator in OpenAI Gym in Python. Used evolving gaussian process to model thermals.}
		\item {Formulated input to agent in a simplified fashion such that only direction of features or rate of change of features without magnitude.}
		\item {Training an agent using SARSA resulted in successfully reducing rate of altitude loss, outperforming random policy and freefall.}
	{}
	\end{cvitems}}

	\vspace{-4mm}
	\cventry
	{}
	{Autonomous ground robot.}
	{Champaign, IL}
	{}
	{\vspace{-4mm}
	\begin{cvitems}
		\item {Implemented path planning, tracking, localization, obstacle avoidance, object detection and classification algorithms using ROS.}
		\item {Research and set plans to implement state-of-the-art stereo cameras and LIDAR based algorithms for objective detection, localization and classification to solve an open problem.}
	{}
	\end{cvitems}}
	
	\vspace{-4mm}
	\cventry
	{}
	{Start ups and Entrepreneurial experiences:}
	{}
	{}
	{\vspace{-3mm}
	\begin{cvitems}
		\item{Engaged and consulted multiple startups in the appliances, consumer electronics, training and development, engineering consulting, etc. Most notable SIILCO: a local appliance company with multmillion dollar investment and valuation.}
		\item{Founded, developed and sold a couple of micro businesses. In the food, health and technology sectors}
	\end{cvitems}}
	
	\vspace{-4mm}
	\cventry
	{Production Engineer - Machinery Diagnostics Engineer}
	{Saudi Basic Industries Corp}
	{Aljubail, SA}
	{Mar 2011 – Jan 2015}
	{\begin{cvitems}
		\item{Provided Technical Engineering support for rotating equipment to 90 SABIC affiliates around the world}
		\item{Initiated, studies and oversaw implementation of lean manufacturing techniques leading to world record breaking productions throught change management techniques.}
		\item{Lead efforts to revise, rewrite and publish standard operating procedures on multi-organization scale.}
		\item{Co-created a global platform for knowledge and expertise sharing as one of handful certified CatIII vibration analysts in the middle east.}
		\item {Conducted the first of it's kind big data analysis on production and machinery data to improve global productivity and reliability.}
		\end{cvitems}}
\end{cventries}
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     Experience
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%\vspace{-2mm}
%\cvsection{Experience \& Projects}
%\begin{cventries}
	
			
%\end{cventries}
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     Skills
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%

\vspace{-5mm}
\cvsection{Skills and Interests}
\begin{cventries}
	\cventry
	{}
	{\vspace{-3mm}\def\arraystretch{1.15}{\setlength{\tabcolsep}{12pt} \begin{tabular}{ l  l l }
		Technical:  & {\skill{ Python (Tensorflow, Keras, Pytorch, OpenCV, Openai Gym), C++, MATLAB, ROS}} \\
		%Interests:  & {\skill{ Mentoring undergrads and peers, fishing, biking, scuba diving, boxing, and debate. }} \\
		%   & {\skill{ Ask me where my best fishing spots are, I just might tell you! }} \\
		\end{tabular}}
	}
	{\vspace{-3mm}}
	{\vspace{-3mm}}
	{\vspace{-3mm}}
\end{cventries}


%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
%     Interests
%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%%
\vspace{-14mm}
\cvsection{Interests}
\begin{cventries}
	\vspace{-4mm}
	\cventry
	{}
	{}
	{}
	{}
	{\textbf{Mentorship:} I am a big believer in giving back and mentorship. I have had active mentors in life and regularly engage in peer mentorship to undergrads, grads and work peers.}
	
	\vspace{-4mm}
	\cventry
	{}
	{}
	{}
	{}
	{\textbf{Hobbies:} I really enjoy biking, fishing, scuba diving, and friendly debates. Ask me where my best fishing spots are, I just might tell you!}
	
\end{cventries}

\end{document}
