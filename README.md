# FairPlayKeyData-Info

FairPlayKeyData es la clave para un activación completa de cualquier dispositivo.

Cuando es generado un FairPlayKeyData durante el llamado al servidor de activación correctamente, este se decodifica en rutas distintas

/private/var/containers/Data/System/com.apple.fairplayd.H2/Documents/Library/FairPlay/iTunes_Control/iTunes/IC-Info.sisv
/private/var/containers/Data/System/com.apple.fairplayd.H2/Documents/Media//iTunes_Control/iTunes/IC-Info.sidv
/private/var/mobile/Library/FairPlay/iTunes_Control/iTunes/IC-Info.sisv

¿Como saber realmente el contenido de estos archivos => IC-Info?

Pongamos como ejemplo un certificado FairPlayKeyData decodificado en base64:


---------------------------CERTIFICADO CODIFICADO---------------------------

	<key>FairPlayKeyData</key>
	<data>
	LS0tLS1CRUdJTiBDT05UQUlORVItLS0tLQpBQUVBQWZkYTltMmdvbWdZMHVlWW1WZ0Y0
	TG5rT1NMeGNDVHZZeHo2djJJUkJLZE1GaU5zOVh1SFdjN1MrVC9BCmlicDNoNk1jTUsw
	YURMUmd3Q25VOGJoUldSb0l4WmhaVUwwbkNwNVdQNEhLdVQyRHZQSEw2SmxQZXl6KzBl
	NGkKNUJsSWlSblc0b0N0TGhQaFV0WUR5TG1zaEI1cnU1cUh6cG1FcWhEbFN2SkhCYUtC
	Y0wySnB3ME0zQ1VqQ3ltOQo0NTQvOXB2eUpHTitZYTBYYVlYZERFMkFTMThlcHhwVk01
	enlSR1piMVpvQlk2UFE5aThSOFBKemV1VVRDMnEyCjZoSkh2UzJJcjlxWmVxd0R2V3A3
	MU1VaUpQNkJMTGluWngybkVHaVlXTDUwOWQzV0lKQjY0Q0gxUHRSTXVUZTIKbUQ3RU9r
	bWFBYWlUd1RCNkpNdS9teGRCVUtVcjFjZ1dPKzRsbVV2REJ2OTJZRUVhV3VVNXB0Yzl3
	OWVXTndYcwo1UTlnUkVmbXYyOTI3dCs5K0UyMS9VR1BiOC8vSlMrQnlHeHQvTE5DcGk5
	dm9TUlhveHA2YjEzNzUwNFluN2cyCmdFclV2TjVYSldIVHh2cXY2TkNoRHVzRWFLV3hk
	SUw0enZnQ1lWdzFwWkxORDZ2UVdqWWxZUlJPV1lUdktDWlkKRVJ1c0s1ZlJlZndUUVN2
	RDh2d1JRNldwL1FGTFpRdmQyNWtGYmg1SUh5YlZYcUkyODFQTldNM2ltQm80a1VFVQpR
	VjNEakR4MVVta1I1UTNpeStWZk5PSVhpdFhxZzNuNGpjN2VITXcvd3ZGdnZ5Qi8vaVlS
	eTFHWit0cG1hVGRlCjlpMDdyUUptSkpFUk1OelE1dk1NQTlnZ2VxbzhJY0ZHZW4wc05p
	SXRqQ3oyVjZ5eGU4ZGljWmlEanorM1pRUk0KdURJMWloZTZWUW0zc3lJRVdyYUd2NWdM
	L3BxSTZuQlJ1MlpMMlc4dU5BenZ0VWNncFE5TWtRTEdXVk5WQWdiRQpZS3JqdThMdFIr
	OTJjaWhBRndJc2d5aVY0TGFSREl3c1JhWk5Nc3VpNkNodWxUMDB6MVJKaW1jRlpmRGo4
	Y1V6CmpxSlRkREhyZjUvbnBRWWRndmRiY3luRG1malE5My9KbmNtVkNHV1FnbFYyNU96
	b3V2U2p4Uk1uL3BzMmlMcHIKZ2U3Vk1aVEFoL3ptZVhTN3JpbldKMUMxUWsvb0gzR2R5
	UmJhWVZBWGFCT1RYS0lhbmVzd3AveXlES1hGN2FsMApibU5OQmxvUEFLdkdIeGFmdy9M
	b2JhVWVoMkNSa2ZmMmxDWDhscmd5UnZTamVPNE9UQVo2WUw4K2ZZNW9iYjlqCk9zUVVL
	bW1KVUwxdVJVVERMQkRjaEU3bmxhMDl5dGRiZEJWeEpxeUNCdGsrcU5lUEhLSi82dVZW
	Uk5tTDUwdTAKZndMc2dUb1B2Ulg1ejdlM08wU2R6Y1hNRFNKWGJMTlU1eCtkajVmbXVw
	S3lnT3V3a2VvbU5sWlkzU1h4eHA5dgpFQ2xjTCsvL2MwQXJldlZlMXYySjRrSXcvSklI
	MU5sVlNmaWhYWHdNZHRnS1ZxNkhtQ2lSYW1iWlA3ZExCUlMrCnFiVklOYnp0UTRNSExK
	MldLRFg4SnkvbzFPbktzOWpENjZFSVNqTmk5UXRETlFuS2x0WW9HTXhuOVBldi85UG8K
	clloRFpmS053Qkl3VDhLTnB4c3BDbkswUHd5eWRONGJ1aS80ajV5V0l4Z0tBaThLamF6
	WmhHU2o2Q3hrK2xQRApDdXdvcm5ueGlXS0NaSnE3eEV1NjZQWnlodlNXNCtRZXZTVTNM
	U0dKS3dONmRKc2J5KzgydHJXWmdkR3FlTEZCCk1PYmxsMm9IRng1aGtmOUFJWW1WdExY
	TmRkejZrYzYza2JGeXRwSld0d0k2c0NoN1RFWlQ3TGRuZ2RMUDBQNWcKK1ZNbk5SWEZz
	dDJEMkZ4cVhsdGpLQXR3L213cm5TOFZQRlZCMkx6Z1lWVkdPdiswCi0tLS0tRU5EIENP
	TlRBSU5FUi0tLS0tCg==
	</data>




---------------------------CERTIFICADO DECODIFICADO---------------------------

FairPlayKeyData decodificado en base64:

	-----BEGIN CONTAINER-----
	AAEAAfda9m2gomgY0ueYmVgF4LnkOSLxcCTvYxz6v2IRBKdMFiNs9XuHWc7S+T/A
	ibp3h6McMK0aDLRgwCnU8bhRWRoIxZhZUL0nCp5WP4HKuT2DvPHL6JlPeyz+0e4i
	5BlIiRnW4oCtLhPhUtYDyLmshB5ru5qHzpmEqhDlSvJHBaKBcL2Jpw0M3CUjCym9
	454/9pvyJGN+Ya0XaYXdDE2AS18epxpVM5zyRGZb1ZoBY6PQ9i8R8PJzeuUTC2q2
	6hJHvS2Ir9qZeqwDvWp71MUiJP6BLLinZx2nEGiYWL509d3WIJB64CH1PtRMuTe2
	mD7EOkmaAaiTwTB6JMu/mxdBUKUr1cgWO+4lmUvDBv92YEEaWuU5ptc9w9eWNwXs
	5Q9gREfmv2927t+9+E21/UGPb8//JS+ByGxt/LNCpi9voSRXoxp6b137504Yn7g2
	gErUvN5XJWHTxvqv6NChDusEaKWxdIL4zvgCYVw1pZLND6vQWjYlYRROWYTvKCZY
	ERusK5fRefwTQSvD8vwRQ6Wp/QFLZQvd25kFbh5IHybVXqI281PNWM3imBo4kUEU
	QV3DjDx1UmkR5Q3iy+VfNOIXitXqg3n4jc7eHMw/wvFvvyB//iYRy1GZ+tpmaTde
	9i07rQJmJJERMNzQ5vMMA9ggeqo8IcFGen0sNiItjCz2V6yxe8dicZiDjz+3ZQRM
	uDI1ihe6VQm3syIEWraGv5gL/pqI6nBRu2ZL2W8uNAzvtUcgpQ9MkQLGWVNVAgbE
	YKrju8LtR+92cihAFwIsgyiV4LaRDIwsRaZNMsui6ChulT00z1RJimcFZfDj8cUz
	jqJTdDHrf5/npQYdgvdbcynDmfjQ93/JncmVCGWQglV25OzouvSjxRMn/ps2iLpr
	ge7VMZTAh/zmeXS7rinWJ1C1Qk/oH3GdyRbaYVAXaBOTXKIaneswp/yyDKXF7al0
	bmNNBloPAKvGHxafw/LobaUeh2CRkff2lCX8lrgyRvSjeO4OTAZ6YL8+fY5obb9j
	OsQUKmmJUL1uRUTDLBDchE7nla09ytdbdBVxJqyCBtk+qNePHKJ/6uVVRNmL50u0
	fwLsgToPvRX5z7e3O0SdzcXMDSJXbLNU5x+dj5fmupKygOuwkeomNlZY3SXxxp9v
	EClcL+//c0ArevVe1v2J4kIw/JIH1NlVSfihXXwMdtgKVq6HmCiRambZP7dLBRS+
	qbVINbztQ4MHLJ2WKDX8Jy/o1OnKs9jD66EISjNi9QtDNQnKltYoGMxn9Pev/9Po
	rYhDZfKNwBIwT8KNpxspCnK0PwyydN4bui/4j5yWIxgKAi8KjazZhGSj6Cxk+lPD
	CuwornnxiWKCZJq7xEu66PZyhvSW4+QevSU3LSGJKwN6dJsby+82trWZgdGqeLFB
	MObll2oHFx5hkf9AIYmVtLXNddz6kc63kbFytpJWtwI6sCh7TEZT7LdngdLP0P5g
	+VMnNRXFst2D2FxqXltjKAtw/mwrnS8VPFVB2LzgYVVGOv+0
	-----END CONTAINER-----



Vamos a eliminar las llaves => -----BEGING CERTIFICATE----- & -----END CERTIFICATE-----

Generando así solo el contenido del certificado:


	AAEAAfda9m2gomgY0ueYmVgF4LnkOSLxcCTvYxz6v2IRBKdMFiNs9XuHWc7S+T/A
	ibp3h6McMK0aDLRgwCnU8bhRWRoIxZhZUL0nCp5WP4HKuT2DvPHL6JlPeyz+0e4i
	5BlIiRnW4oCtLhPhUtYDyLmshB5ru5qHzpmEqhDlSvJHBaKBcL2Jpw0M3CUjCym9
	454/9pvyJGN+Ya0XaYXdDE2AS18epxpVM5zyRGZb1ZoBY6PQ9i8R8PJzeuUTC2q2
	6hJHvS2Ir9qZeqwDvWp71MUiJP6BLLinZx2nEGiYWL509d3WIJB64CH1PtRMuTe2
	mD7EOkmaAaiTwTB6JMu/mxdBUKUr1cgWO+4lmUvDBv92YEEaWuU5ptc9w9eWNwXs
	5Q9gREfmv2927t+9+E21/UGPb8//JS+ByGxt/LNCpi9voSRXoxp6b137504Yn7g2
	gErUvN5XJWHTxvqv6NChDusEaKWxdIL4zvgCYVw1pZLND6vQWjYlYRROWYTvKCZY
	ERusK5fRefwTQSvD8vwRQ6Wp/QFLZQvd25kFbh5IHybVXqI281PNWM3imBo4kUEU
	QV3DjDx1UmkR5Q3iy+VfNOIXitXqg3n4jc7eHMw/wvFvvyB//iYRy1GZ+tpmaTde
	9i07rQJmJJERMNzQ5vMMA9ggeqo8IcFGen0sNiItjCz2V6yxe8dicZiDjz+3ZQRM
	uDI1ihe6VQm3syIEWraGv5gL/pqI6nBRu2ZL2W8uNAzvtUcgpQ9MkQLGWVNVAgbE
	YKrju8LtR+92cihAFwIsgyiV4LaRDIwsRaZNMsui6ChulT00z1RJimcFZfDj8cUz
	jqJTdDHrf5/npQYdgvdbcynDmfjQ93/JncmVCGWQglV25OzouvSjxRMn/ps2iLpr
	ge7VMZTAh/zmeXS7rinWJ1C1Qk/oH3GdyRbaYVAXaBOTXKIaneswp/yyDKXF7al0
	bmNNBloPAKvGHxafw/LobaUeh2CRkff2lCX8lrgyRvSjeO4OTAZ6YL8+fY5obb9j
	OsQUKmmJUL1uRUTDLBDchE7nla09ytdbdBVxJqyCBtk+qNePHKJ/6uVVRNmL50u0
	fwLsgToPvRX5z7e3O0SdzcXMDSJXbLNU5x+dj5fmupKygOuwkeomNlZY3SXxxp9v
	EClcL+//c0ArevVe1v2J4kIw/JIH1NlVSfihXXwMdtgKVq6HmCiRambZP7dLBRS+
	qbVINbztQ4MHLJ2WKDX8Jy/o1OnKs9jD66EISjNi9QtDNQnKltYoGMxn9Pev/9Po
	rYhDZfKNwBIwT8KNpxspCnK0PwyydN4bui/4j5yWIxgKAi8KjazZhGSj6Cxk+lPD
	CuwornnxiWKCZJq7xEu66PZyhvSW4+QevSU3LSGJKwN6dJsby+82trWZgdGqeLFB
	MObll2oHFx5hkf9AIYmVtLXNddz6kc63kbFytpJWtwI6sCh7TEZT7LdngdLP0P5g
	+VMnNRXFst2D2FxqXltjKAtw/mwrnS8VPFVB2LzgYVVGOv+0


Finalmente decodificamos este certificado, obteniendo así => IC-Info.sisv & IC-Info.sidv


---------------------------IC-Info/sisv/sidv---------------------------

	  ÷Zöm ¢hҧX๤9"񰤯cú¿b§L#lõ{YΒù?Àºw£0­´`À)Ա¸QYŘYP½'
	V?ʹ=¼񋨙O{,þѮ"䙈֢­.ᒖȹ¬k»Ιª劲G¢p½§
	 ܥ#)½㞿ö򤣾a­i݌MK_§U3򄦛՚c£ж/𲳺哋j¶ꒇ½-¯ڙz¬½j{ԅ"$þ,¸§g§hX¾tõݖ zࡵ>Ԍ¹7¶>ĺI¨Á0z$˿AP¥+Ո;KÆÿv`AZ幦׽×7쥏`DG濯vøMµýAoϿ%/Ȭmü³B¦/o¡$W£zo]û玘¸6JԼޗ%aӆú¯萡넨¥±tøθa\5¥͏«К6%aNY都X¬+ѹüA+òüC¥©ýKeݛnH&՞¢6󓍘͢8AA]Ì<uRi卢˥_4◊ժyøΞ̿±o¿ þ&ˑúڦi7^ö-;­f$0ܐ泌ؠzª<!ÁFz},6"-,öW¬±{Ǣq?·eL¸25ºU	·³"Z¶¿þ갑»fKٯ.4﵇ ¥LƙSUĠª㻂퇯vr(@,(එ,E¦M2ˢ訮=4ϔIge𣱅3¢St1뿟祆÷[s)ÙøзɝɕeUv䬨º��'þ6ºkÀü湴»®)֧PµBO蟱ɖڡPh\¢밧ü²¥ŭ©tncMZ «Ɵò譥`÷ö%ü¸2F��Lz`¿>}hm¿c:Ĕ*iP½nEDì܄N畭=ʗ[tq&¬پ¨׏¢꥕Dً狴쁺½ùϷ·;D̍ͅ"Wl³T矝溒²밑ꦶVXݥ񆟯)\/￳@+zõ^ֽ₰üԙUIø¡]|v؊V®(jfٿ·K¾©µH5¼탃,(5ü'/蔩ʳ؃롈J3bõC5	ʖ֨̧��Ө­Ce򍀒0O§)
	r´?²tޛº/ø#
	/
	¬لd£謤úSÊ쨮y񉢂d»ċº趲��½%7-!+zt˯6¶µѪx±A0楗jaÿ@!´µ͵ܺη±r¶V·:°({LFS췧ҏо`ùS'5Ų݃؜j^[c(pþl+/<UAؼࡕF:ÿ´
