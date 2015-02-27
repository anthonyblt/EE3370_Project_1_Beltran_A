Edits:	line 1: 	% EE3370 Project 1
	line 2:  	% MATLAB code for Project 1
	line 3: 	% Anthony Beltran
	line 4:  	% 2/27/2015
	line 10:  	t=linspace(-3000*T,3000*T,1000);
	line 12:	subplot(4,1,1)
	line 14:	subplot(4,1,2)
	line 17:	subplot(4,1,3)
	line 18: 	plot(t,x_t.*u_t, 'linewidth',2);grid on


Added:	line 19:	u_t1 = heaviside(t-1);
	line 20:	x_t1 = cos(omega.*t).*sin(omega.*t).*u_t1;
	line 21:	subplot(4,1,4);
	line 22:	plot(t,x_t1, 'linewidth',2);grid on

(Updated Working Copy)  -Anthony
