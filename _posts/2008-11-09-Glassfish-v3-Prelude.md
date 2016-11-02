---
layout: inner
title: 'Glassfish v3 Prelude'
date: 2008-11-09 23:13:53
categories: Boletim
tags: glassfish java sun
post_author: Leandro
comments: false
lead_text: 'Na sexta-feira, dia 07 de novembro foi publicada uma versão prévia do Glassfish v3 Prelude, o servidor JEE opensource da Sun, e a implementação de referência JEE 6. Entre as muitas novidades desta versão, destaca-se a mudança arquitetural, através de módu...'
---

<p style="text-align: justify;"><a href="img/glassfish-logo-140_92.jpg"><img class="alignright size-full wp-image-168" title="glassfish-logo-140_92" src="img/glassfish-logo-140_92.jpg" alt="" width="140" height="92" /></a>Na sexta-feira, dia 07 de novembro foi publicada uma versão prévia do<a href="https://glassfish.dev.java.net/public/comparing_v2_and_v3.html"> Glassfish v3 Prelude</a>, o servidor JEE opensource da Sun, e a implementação de referência JEE 6. Entre as muitas novidades desta versão, destaca-se a mudança arquitetural, <a href="http://www.infoworld.com/article/08/11/05/Sun_offers_OSGi_app_server_1.html">através de módulos gerenciados por um contêiner OSGi</a> (que introduz essa tecnologia em produtos Sun e a iniciativa da empresa em apoiar esta especificação) e seu suporte à linguagens dinâmicas.</p>
<p style="text-align: justify;">Sobre o suporte à <a href="http://www.infoworld.com/article/08/11/05/Sun_offers_OSGi_app_server_1.html">OSGi</a>, cabe salientar que o suporte é interno, para módulos do próprio servidor e não para aplicações que façam uso dessa tecnologia assim como no Spring DM Server. Atualmente é utilizado o projeto Apache Felix que, obviamente pode ser trocado por qualquer outra implementação OSGi, como o Eclipse Equinox.</p>
<p style="text-align: justify;">Já sobre linguagens dinâmicas, a nova arquitetura permite instalar plugins para suporta-las. Estão disponíveis pacotes para Groovy e Grails, JRuby on Rail, PHP e Scala/Lift. Mais detalhes dessa integração podem ser vistos no blog do Vivek Pandey.</p>
<p style="text-align: justify;">Além de todos os recursos citados acima, temos APIs relacionadas à JDK e JEE onde cabe destacar a implementação JPA 2.0, o framework jMaki com componentes JSF e taglibs JSP para AJAX, Grizzly para Comet, o projeto Metro para webservices e Jersey para serviços REST, JSF 2.0, EJB 3.1 e muito mais!</p>