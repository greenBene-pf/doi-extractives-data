---
title: Öffentliche Berichte
layout: default
permalink: /rohstoffgewinnung/offentliche-berichte/
breadcrumb:
  - title: Deutscher Rohstoffsektor
    title_en: German Commodities Sector
    permalink: /rohstoffgewinnung/
---
<link rel="stylesheet" type="text/css" href="{{ site.baseurl_root }}/css/slick-theme.css"/>
<link rel="stylesheet" type="text/css" href="//cdn.jsdelivr.net/jquery.slick/1.6.0/slick.css"/>

<main class="container-page-wrapper layout-state-pages">
  <section class="container" style="position: relative;">

    {% include breadcrumb.html %}
    <h1 id="title">{% t offentliche-berichte.title %}</h1>

    <div class="container-left-9">
      <section id="offentliche-berichte" style="position: relative;">
        <section id="gesetzliche-berichtspflicht" style="position: relative;">
          <h2 id="title">{% t offentliche-berichte.gesetzliche-berichtspflicht.title %}</h2>
          <p>
            {% t offentliche-berichte.gesetzliche-berichtspflicht.p1 %}
          </p>
          <br/>
          <ol>
            <li>{% t offentliche-berichte.gesetzliche-berichtspflicht.l1 %}</li>
            <li>{% t offentliche-berichte.gesetzliche-berichtspflicht.l2 %}</li>
            <li>{% t offentliche-berichte.gesetzliche-berichtspflicht.l3 %}</li>
          </ol>
          <p>
            {% t offentliche-berichte.gesetzliche-berichtspflicht.p2 %}
          </p>
          <p>
            {% t offentliche-berichte.gesetzliche-berichtspflicht.p3 %}
          </p>
        </section>
        <br/>
        <section id="gemeinsamkeiten" style="position: relative;">
          <h2 id="title">{% t offentliche-berichte.gemeinsamkeiten.title %}</h2>
          <p>
            {% t offentliche-berichte.gemeinsamkeiten.p1_1 %}
            <a href="{{site.baseurl}}/daten/zahlungsabgleich/">
            {% t offentliche-berichte.gemeinsamkeiten.link1 %}
            </a>
            {% t offentliche-berichte.gemeinsamkeiten.p1_2 %}
          </p>
          <p>
            {% t offentliche-berichte.gemeinsamkeiten.p2_1 %}
            <a href="{{site.baseurl}}/daten/zahlungsabgleich/">
            {% t offentliche-berichte.gemeinsamkeiten.link2 %}
            </a>
            {% t offentliche-berichte.gemeinsamkeiten.p2_2 %}
          </p>
          <p>
            {% t offentliche-berichte.gemeinsamkeiten.p3 %}
          </p>
        </section>
      </section>
    </div>

    <div class="sticky sticky_nav container-right-3">
      <h3 class="state-page-nav-title container">
        <div class="nav-title">{% t offentliche-berichte.title %}</div>
      </h3>
      <nav>
        {% assign nav_items = site.translations[site.lang]['offentliche-berichte'].nav_items %}
        {% include case-studies/_nav-list.html nav_items=nav_items %}
        {% include layout/share-buttons.html %}
      </nav>
    </div>
  </section>
</main>

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script type="text/javascript" src="//cdn.jsdelivr.net/jquery.slick/1.6.0/slick.min.js"></script>
<script type="text/javascript" src="{{ site.baseurl_root }}/js/lib/static.min.js" charset="utf-8"></script>
