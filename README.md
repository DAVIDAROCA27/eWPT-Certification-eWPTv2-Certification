# Certificación eWPTv2 - Guía y Opinión Personal

<img width="1102" height="851" alt="image" src="https://github.com/user-attachments/assets/9c11e1b6-5745-469a-8a29-21384e2c1024" />

## Mi opinión sobre el examen

Lo primero: no creo que sea un examen complicado, pero necesitas tener una buena base.

**Sobre el precio:** No vale la pena comprar el voucher de 600$ con acceso a la formación del INE. Tampoco creo que valga la pena gastarse 400$ por el voucher normal. En mi caso, todas las certificaciones del INE las conseguí con descuento del 50% (eJPT, CPPT y eWPT). Por unos 400$ pude conseguir las tres. De otra forma, no vale la pena en mi opinión personal.

Esta gente suele sacar descuentos cada 3-4 meses. Lo que hice fue dejarme la pestaña del INE fijada en el navegador y entrar a revisar todos los días durante bastantes semanas.

Yo me preparé mucho para hacerlo y luego me decepcioné un poco. Me daba cosa las 10 horas de examen, pensando que no me iba a dar tiempo, pero en 5-6 horas una persona normal puede terminarlo. A mí siempre me gusta estar hasta el último minuto y sacar todo el jugo.

## El examen

El examen deja bastante que desear desde mi opinión. Cualquier máquina fácil de HackTheBox me parece más complicada. No necesariamente tienes que explotar los servicios ni elevar privilegios una vez dentro. No es un CTF y no os lo toméis como tal.

Es un entorno con X máquinas con X puertos abiertos. Como en cualquier examen de este tipo, la enumeración es crucial, solo que aquí la mayoría de puertos abiertos son web, lo que podría variar de otros exámenes.

## Recursos recomendados

- **Laboratorios de PortSwigger:** Yo solo hice los de SQLI y XSS, y con eso ibas más que preparado.
  - https://portswigger.net/web-security/all-labs
  - Hacer CTF's de tryhackme y sitios como THEHACKERLABS aqui esta un excel con todas las maquinas para practicar https://docs.google.com/spreadsheets/d/1lt81_6Uor1v6O7vvnafnYm8mciINVIspiLYiDbnDOD8/edit?usp=sharing

## Consejos y cosas a tener en cuenta

- **Vulnerabilidades clave** que me tocaron: LFI, XSS (Reflected/Stored) y SQLI. Nada complejo, todas muy simples con payloads básicos.

- **Herramientas:** Utilizar nuclei/nikto para cada URL. No os calentéis la cabeza, os sacará prácticamente todo.

- **Conocimientos necesarios:**
  - Fuzzing básico de APIs
  - Manipulación de COOKIES y criptografía básica
  - Enumeración exhaustiva y correcta
  - Hash cracking (muy básico)
  - OWASP TOP10 (para guiar enumeración y explotación)

- **⚠️ Advertencia importante:** No utilizar feroxbuster. El binario está en la máquina pero si lo ejecutas, te cargarás el entorno entero y tendrás que reiniciar.

- **CMS:** Saber hackear CMS comunes. Preguntad a ChatGPT cuáles eran los 3 CMS más comunes hace 5-10 años y os lo dirá. Saber trabajar con las herramientas para enumerar usuarios, sacar bases de datos y moveros con soltura.

- **Importante:** No es necesario explotar servicios en muchas ocasiones, ni escalar privilegios dentro de las máquinas. Todo se puede hacer desde fuera sin complicaciones, al menos para las preguntas que yo tenía.

- **Servidores Web:** Tener conocimientos sobre servidores web y su explotación.
