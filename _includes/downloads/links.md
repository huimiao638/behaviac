{% assign linkBase = site.download.base %}
{% capture linkMin %}{{ linkBase }}behaviac-{{ version }}{{ site.download.type.min.suffix }}{% endcapture %}
{% capture linkSrc %}{{ linkBase }}behaviac-{{ version }}{{ site.download.type.src.suffix }}{% endcapture %}
* [{{ linkMin }}]({{ linkMin }})（{{ site.download.type.min.title }}）
* [{{ linkSrc }}]({{ linkSrc }})（{{ site.download.type.src.title }}）