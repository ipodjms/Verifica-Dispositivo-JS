				
				platform = navigator.platform;
				
					// faz alguma coisa se for Iphone ou Androis mobile
				if ((platform != 'iPhone') && (platform != 'Android') && (platform != 'Linux armv7l')  && (platform != 'Linux armv6l') ) {					
  				// faça algo aqui
				}
				
				
						// faz alguma coisa que nao for ipad, nem mac, nem windows...
				if ((platform != 'iPad') || (platform == 'MacIntel') || (platform == 'Win32') || (platform == 'Win64')) {
		      // faça algo aqui
				}
				
				
				
				se nao for iphone, android, qualquer ie , windows phone e ie mobile
				if (platform != 'iPhone' && platform != 'Android' && !(navigator.userAgent.indexOf("MSIE 7.0") > 0) && !(navigator.userAgent.indexOf("MSIE 8.0") > 0) && !(navigator.userAgent.indexOf("MSIE 9.0") > 0) && !(navigator.userAgent.indexOf("MSIE 10.0") > 0) && !(navigator.userAgent.indexOf("Windows Phone") > 0) && !(navigator.userAgent.indexOf("IEMobile") > 0)) {					
           // faça algo aqui
        }  
				
				
