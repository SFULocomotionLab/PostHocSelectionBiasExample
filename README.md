# PostHocSelectionBiasExample
A typical experimental design involves applying a range of treatments to different participants and testing if these treatments have an effect. This is a good experimental design if one tests whether treatment A has an effect compared to the null condition, for example. But one thing that is not
% OK is to select the treatment that has the largest effect for each
% participant (treatment B for participant 1, treatment C for participant
% 2, etc.), averaging these effects across participants, and then
% concluding that customized treatments have a net effect. Because of the
% random variability in measurements, where some measurements are higher
% and some are lower by chance and not by treatment, it is very likely to
% find an effect where none is present. 
%
% This simple script demonstrates this using data from the following
% exoskeleton paper as an example:
% Barazesh H, Ahmad Sharbafi M. A biarticular passive exosuit to support
% balance control can reduce metabolic cost of walking. Bioinspir Biomim
% [Internet]. 2020 Jan 28 [cited 2020 Feb 11]; Available from:
% https://iopscience.iop.org/article/10.1088/1748-3190/ab70ed
%
% This paper suffers from this problem, but it is by no means the only one.
% Indeed, the whole field of psychology has been trying to overcome this
% and similar defficiencies recently.
%
% Written by Max Donelan on Feb 11 2020
 
