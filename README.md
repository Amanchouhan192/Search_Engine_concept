import webbrowser
p = ('........<a href="www.youtube.com"</a>....')


sl =(p.find('<a href'))#p= page , sl = start link#sq = start quote
sq =(p.find('"',sl))#eq = end quote
eq =(p.find('"',sq + 1))
url =(p[sq + 1:eq])
print(url)
webbrowser.open(url)


x = ('...<a href="www.facebook.com"</a>....')
sl =(x.find('<a href'))#p= page , sl = start link#sq = start quote
sq =(x.find('"',sl))#eq = end quote
eq =(x.find('"',sq + 1))
link =(x[sq + 1:eq])
print(url)
webbrowser.open(link)

