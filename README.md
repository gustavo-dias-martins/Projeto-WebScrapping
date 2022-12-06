<h1> Projeto WebScrapping </h1> 
<p>O projeto é um código desenvolvido em Python, desenvolvido no Jupyter que consiste em automatizar, utilizando o Selenium, a busca de produtos no em dois sites de busca: o Google Shopping e o Buscapé.</p>

<h2> Bibliotecas Utilizadas </h2>
<p>- Selenium</p>
<p>- Pandas</p>
<p>- smtplib</p>
<p>- email.message</p>
<p>- mimetypes</p>
<p>- OS</p>

<h2> O que temos disponível? </h2>
<p>- Planilha "buscas.xlsx", com os nomes dos produtos, o preço máximo, o preço mínimo (para evitar produtos "errados" ou "baratos de mais para ser verdade" e os termos que vamos querer evitar nas nossas buscas.</p>

<h2> Como funciona? </h2>
<p>Imagina que você trabalha na área de compras de uma empresa e precisa fazer uma comparação de fornecedores para os seus insumos/produtos. Nessa hora, você vai constantemente buscar nos sites desses fornecedores os produtos disponíveis e o preço, afinal, cada um deles pode fazer promoção em momentos diferentes e com valores diferentes, nesse caso no Google Shopping e Buscapé.

Se o valor dos produtos for abaixo de um preço limite definido por você, você vai descobrir os produtos mais baratos e atualizar isso em uma planilha "Ofertas.xlsx".

Em seguida, vai enviar um e-mail com a lista dos produtos abaixo do seu preço máximo de compra com a notificação e a tabela com os itens e preços encontrados, junto com o link de compra.</p>
