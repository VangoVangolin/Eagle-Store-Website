# Eagle-Store-Website
This is the main page for the website

<!DOCTYPE html>
	<!--Este va a ser el titulo del website-->
	<head>
		<title> Eagle Store Website </title>
		<link rel="icon" href="https://lh3.googleusercontent.com/WiOPVrVKR0_vfL8-17I1HN5U7n3-RWVoUS-RAQJvrYstZV3TX4iyOmhuSh_F_ue44H-iDvkw3tG8ioBdsOAMdxcebJSLl9QZL-V26Cksh6qPVHIFmXg41QXcSmgqqJc3GLtSM4AQ2AGeyRNwD2y5kVQRsvPo2IvwWeX4embp-7Jkxh8aeg-A_fsJmopwPMJC8FstiWv0CDXJVc_vykcKFRTtIBg5yfx1-aKsJqmatG7x66s-TXkVNwE79edCrLsDjsy7mwI2ykN5weInUb_NOi-lqFISwq-FL6xVBjOClYaZjaWQc62EFk7b2O2hzxUVwh6l2pG1g6isXNzj1VcrfCHKXa5Lb0da719ZADmeMiTBTxJD8GhTvr7dzawjPqzsmKBk0bb1R779xqBHzXb2yAcsdajiEIceD0EPl7tB3f2J8dYLj-rbK8IQmeZeAqstzf2cZddkcTsYMPX1O5Rvk9lZq7xDGk59s5fg5J8WQtL5ta7z4At52a5KWJRUJ97zcT0r8SFBIjlRT-1gZqMQTA3rHuUCQd4JfltxXX8Ts_uo8nEDCna9jQPjU4WGbbg5MObq9D-aUGPMXi13y6OtCfS-QL40sTmzms6EskE11-Uu1z9y=s1283-no">
	<style>
		body {
			background-color: f9f9f9;
		}
		div.everything {
			margin-left: 200px;
			margin-top: -55px;
		}
		div.logo {
			margin-left: 300px;
			margin-top: 0px;
		}
		
		span.first {
			display: inline-block;
			margin-left: 25px;
            
			
		}

		span.lineal {
				display: inline-block;
				padding-left: 40px;
                
		}
		
		a:link{
			display: block;
			background-color: rgb(244,244,244);
			/*original color was: rgb(244,244,244)*/
			height: 300px;
			width: 300px;
			color: none;
			text-decoration: none;
             border-radius: 100%;
			 margin-top:-5px;
			
		}
		a:hover {
			display: block;
			background-color: #34B8B9;
			/*color is medium turquoise, retrieved from: http://www.computerhope.com/cgi-bin/htmlcolor.pl?c=48CCCD */
			height: 300px;
			width: 300px;
			color: white;
			text-decoration: none;
            border-radius: 100% ;
            animation: shake 0.82s cubic-bezier(.36,.07,.19,.97) both;
            transform: translate3d(0, 0, 0);
            backface-visibility: hidden;
            perspective: 1000px;
			margin-top: -5px;
        }
		a:visited{
			display: block;
			background-color: rgb(244,244,244);
			height: 300px;
			width: 300px;
			color: none;
			text-decoration: none;
             border-radius: 100%;
			 margin-top: -5px;
		}
/*
             @keyframes shake {
                10%, 90% {
                    transform: translate3d(-1px, 100px, 30px);
                }
                
                20%, 80% {
                    transform: translate3d(2px, 6px, 67px);
                }

                30%, 50%, 70% {
                    transform: translate3d(-4px, -45px, 90px);
                }

                40%, 60% {
                    transform: translate3d(4px, -80px, -3px);
                }
            }
*/
			@-webkit-keyframes shake {
			    0%, 100% {-webkit-transform: translateX(0) rotate(0deg) translateY(0);}
			    15%, 35%, 55%, 75%, 95% {-webkit-transform: translateX(-1px) rotate(-2deg) ;}
			    25%, 45%, 65%, 85% {-webkit-transform: translateX(1px) rotate(2deg); }
			    10%, 30%, 50%, 70%, 90% {-webkit-transform: translateY(1px);}    
			    20%, 40%, 60%, 80% {-webkit-transform: translateY(-1px); }
			}
			@-moz-keyframes shake {
			    0%, 100% {-moz-transform: translateX(0) rotate(0deg) translateY(0);}
			    15%, 35%, 55%, 75%, 95% {-moz-transform: translateX(-1px) rotate(-2deg) ;}
			    25%, 45%, 65%, 85% {-moz-transform: translateX(1px) rotate(2deg); }
			    10%, 30%, 50%, 70%, 90% {-moz-transform: translateY(1px);}    
			    20%, 40%, 60%, 80% {-moz-transform: translateY(-1px); }  
			}

			@-o-keyframes shake {
			     0%, 100% {-o-transform: translateX(0) rotate(0deg) translateY(0);}
			    15%, 35%, 55%, 75%, 95% {-o-transform: translateX(-1px) rotate(-2deg) ;}
			    25%, 45%, 65%, 85% {-o-transform: translateX(1px) rotate(2deg); }
			    10%, 30%, 50%, 70%, 90% {-o-transform: translateY(1px);}    
			    20%, 40%, 60%, 80% {-o-transform: translateY(-1px); }  
			}

			@keyframes shake {
			    0%, 100% {transform: translateX(0) rotate(0deg) translateY(0);}
			    15%, 35%, 55%, 75%, 95% {transform: translateX(-1px) rotate(-2deg) ;}
			    25%, 45%, 65%, 85% {transform: translateX(1px) rotate(2deg); }
			    10%, 30%, 50%, 70%, 90% {transform: translateY(1px);}    
			    20%, 40%, 60%, 80% {transform: translateY(-1px); }  
			}
			.shake {
			    -webkit-animation-name: shake;
			    -moz-animation-name: shake;
			    -o-animation-name: shake;
			    animation-name: shake;
			    -webkit-animation-duration: 100s;
			    -moz-animation-duration: 100s;
			    -o-animation-duration: 100s;
			    animation-duration: 100s;
			    -webkit-animation-fill-mode: both;
			    -moz-animation-fill-mode: both;
			    -o-animation-fill-mode: both;
			    animation-fill-mode: both;
			    -webkit-animation-iteration-count: infinite;
			    -moz-animation-iteration-count: infinite;    
			    -o-animation-iteration-count: infinite;
			    animation-iteration-count: infinite;
			    -webkit-transition-timing-function:linear;    
			}
		h1 {
			text-align: center;
			padding-top: 30px;
			font-family: "Trebuchet MS", Helvetica, sans-serif;
			font-variant: small-caps;
			font-size: 43px;
			color: #34B8B9;
		}
		img.circles {
			padding-left: 27px;
			padding-top: 25px;
		}
	</style>

		
	</head>

<body>
	<div class="logo">
		<img src="https://lh3.googleusercontent.com/j_OFkYP6Ttls_fndVd5DXz7hdtaHXpGv8jyBJ85tfiBdRygO5SNJ04XyvPmkurmy6-5074wQvB6HGONOdT6YCWfpzed3NdQDGiMFqsFE1TVa6MvP7R3vkFf8-FPDKxlSEyl2M02Bj92Kp49wEzp3kKHPAN15S2nS9HVBZTn0ZJSMv3-ZWJrwlnbjUsRaPe10dao4rbtPOXdKX0qUTCpTMADUteRN6PLE1q22Tq739hSUDNA7Hcbm5nja__hRNHRyB1pT9hsgGtoofVj7urlEzh-UlIzsR-GuHthI7YUirrj3wFXoc0Cx5e8DIKauS1bNyAp1U2aSYhOCGodIOLpv9abDxfFrfP5jBH1HUwC5vmxV__w9Cy7EkADrgM3-ZmY1vQ2Btd2e4DcpSpBZK35nxVmBYTfol5euwD91na_UObwohvjVIxCNvDjkb4Hut2IeIBjwVNxjLG7GNALGosb2Yv_JyW1HzKmPeSgH1o2tb7bG5R6l_gWMOhRWOlFFvoSRamIW4zCyMqbDl9itUckpqOsSQLLYtmUefVgiuG2okFYXLeOAXybuHva36OWzwUjxw1knEl_PamKdu9DQF0pyoeo1TJ_Lf1HBEuPZ4zFsgkBSKrVO=w1033-h242-no" height="202 px" width= "862 px" />
	</div>
	<!--<div class="banner">
		<img src="https://lh3.googleusercontent.com/h6xCRnm4NZDLrwgOYdQ4tc9-yCQSB4slpK4-3BDgy2wlVaNKEUE7jLGxBZXMh8bHO9IvqmkZnyv66aeud5J2wcD2MnimkZjlYU9TIssOw1IRwlrXRerH3ALZgO_4ib1Z8rjbbTkNO5g2C9Rqrw9-BpFYLn4V50T6GrQW0kE_FYq8cQjDEaVCHR4EvGQ3wSmGA2bbkxvWDtHO8uQ5ld37ITM0kByszXHQqPVRxC_NlpwUyxPFhAgqyjnQ0FruNDykDt3DCole4M3b6l_2t7CEcpjsbWxlBH8gEx_GcAwVCdzpfeOHBIFY1wECdKivBeQCKyYyJT2CsKRxtdE7vvhUrOcVaAkjLYFaWdiHG9DbPQOy6DGuLKnSGSPFaJc3EO3aiF4lQbStQUB2X3fWEI1xpzk6BVI0IElkSI79Au7JtlqJeHeekSpWJA89fzTv6fkveIiy9xDsrM9grUBEG4N4POLRFCWR0cuIrEhu4flpS487XKJGHuSMdpiWleUYRNdxJS3pbIe8N7Bvj-aqTmYQfEHthAoZAnRxkweP-8femGUWTItWyFp0_SOficeKalDG2lsATQpeOvKFReCHspuRDFiBRe6y4BCkrnHuy5qxRw8JIjki=w1639-h504-no" width="1410 px" height="436 px" />
	</div>-->
		<div class="everything">
			<span class="first">
				<h1> Uniforms</h1>
				<a href="C:\Users\Owner\OneDrive\Documents\Eagle Store Web Site\Codes\Uniforms.html">
					<img class="circles" src= "https://lh3.googleusercontent.com/ZYprUDk8N2T7DAwdHE7AgL7gKR0BmCxVwA30z0tRohfaozLs97N3CxuVIsIpEp53O-7n7UoGULIcNidL0p9_RLYQRMEJhvYf0VeGYl31z8qpJYqnj2LwNFTLQ7si1FB9ZEZblTRVF3o71aX_wsrKYFJwN-_66Bz1XJe7xatBR4bIFE3Ryy7N7p8weOVEAe4JG4PYXyUfB6YkKvRhipg0tJkGEVf7T9iY1ncvIiqrhJAHRf48L4XTTxHQPOSU6MR4UhiTFBE5gVmln09uhz8tbfBhcmQqZnQ1L7rSxCtJUFjaHU9mrrjiGEzSG4cb29VaIrP2ptpaWe0V6ygeL7q96L60OkMuX_y_zuf4LLKHKYbnekZSN8h2hFNqcUz9tVuTJBOH3yGoPuNzufUmhEXzQ-j3Ng1MP4jpVG9-dVmLSpzRqLoILSQDBaeSfylhJjsU_CmhxNn7C5Majx7FhUb0r6lqaMB-plk7c_yBsXBvWV6_rvmTLU7LKkKHBFweq-G_nB5uxhdgA_4Sm4VSpLw4K4qM2h0H-2PkKmIp83-KDki1f48691AgBnCJpyCI6mmJ8ScO9pTZyDrZLUdmIyk7zbr0Ujk35E1N6MucbEipz919usQW=s1281-no" height="250px" width="250px" />
				</a>
			</span>

			<span class="lineal">
				<h1> Materials</h1>
				<a href="C:\Users\Owner\OneDrive\Documents\Eagle Store Web Site\Codes\Materials.html">
					<img class="circles" src= "https://lh3.googleusercontent.com/B6pYX_aBHPTyv6JoPO8cDp0BTZkA6yEl9scpApK6Nprg3KZNLA1_xL2Idk9m6Nz091s26x2toMk0i1fbimT7i5TcWAeekccr-Ax46WWrFCgKyVhlNLLSmC3FM3WMcx0Pwxm2uQn64CvmkaL6-usIkPJKe_QMgTCCtSNYsAtSlAR6YGwmID_ghTxey-peZe57U-raUEeqTQsVw7N4joTiRg4cB8mbQ1edbjfDUI-YIVn_KCdU2JrdLwFFYVTX0hraph6RhBF08gzhr5eE-8Gpfw087tnU3c0XxUEm9HAmK50lrWNYwSYusyB9Z1WZ3Y7ptgj4_I8BeWadyo_9aUrdRuQT2YeyAWJXjhbUzEQDfbi5RubuiRkYZmq-Ywa2iCuLgRG2Z0_2H66_hToNuA1FZMtHJBaZfzGoqn-1FR-6TUyg8oiX9VIu7sICWbATM-XruUJNK65ISBdKk485TcQ_ehifkzQ0MLtzErLlIuYDi6GXCSKFces46vSxMJm5uha-Ic9ZCm4jEw4wbErGqTizm-mbowA4cd-OFJqP7JSzJtB9d0s-ERF1IrW85rUcWW0skme2OfhLmbb7ibW0imylHR0i9dmEyfVzxQu1re3an2-ys0zN=s1281-no" height="250px" width="250px" />
				</a>
			</span>

			<span class="lineal">
				<h1>Books</h1>
				<a href="C:\Users\Owner\OneDrive\Documents\Eagle Store Web Site\Codes\Books.html">
					<img class="circles" src= "https://lh3.googleusercontent.com/XvNsNxFcT3YUtWTWA7OBn2WeXdQNac5SKlPRGRnYmVdfj8ArtAzjolixO8o8IrbFTptrq3Kc_Tsz2XPitJdNrL4QY3gc2odqY0ugXKJUPEvy7nn0cqxyU1JRjjX-8bCRtHMW40ELDqVGKEOJviyb2Pdo8iOUFBZe8klfh3CsYyypBvdboMeQPD0NwXCdLgIHR_Tv_K83HVgRxC-mStWF_Al2gbYCtLSqCZEpCm5qOJbca5rO13YUdSIsaOJJBwEDNmtH92hZKkYuQ3VlfbzYgfg0kslx6FFJVpZdLr2Ui-wgD-E05cP4RHAJNNRuhd7pmiIksgjASt_i8qMe9nFMXbtnISBR_cFSCCWjP1eNNsviGsWEo90ApTlCzmY5Yzbf7tJDGubC62l1R-2C4QXdmlKUfT0f0GD3hzwQn1Nk0fdUBD77oPIhoNvEUqkEi6KBvoWEJkerCh7NwzCjO81RbTCZwPO8lax1OoCE7iFR6vPdLkwTLdmHlfgYP3Jz-hg7YkwxZ4ZDfUmsBFHg45EUm40yMksrCFZ-oxYNOf915XPe8w67U9yB9DFaxpDMqCNB1sSdMikxCY76shLl4RmVqqxiOMRauumwNqLZLcjKMgWIEsbi=s1281-no" height="250px" width="250px" />
				</a>
			</span>
		</div>
	</body>
</html>
