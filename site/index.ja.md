<!-- ((! set title OCaml !)) ((! set core !)) ((! set nobreadcrumb !)) -->
<!-- ((! set advertise_rss true !)) -->

<header id="home-header">
    <div class="container">
        <div class="row">
            <h1 class="span9">OCaml は、関数型、手続き型、オブジェクト指向を備えた 強力なプログラミング言語です</h1>
            <div class="span3">
                <div>
                <a class="btn" href="/docs/install.html">OCamlを<br/>ダウンロード</a>
                </div>
            </div>
        </div>
    </div>
</header>
<div class="container core-running-header">
((! input template/running-header.mpp !))
</div>
<div class="container">
    <div class="row home-hero">
        <div class="span8">
            <div class="row">
                <section class="span4 home-feature">
                    <a href="/learn/">
                        <img src="/img/learn-large.png" alt="まなぶ">
                    </a>
                    <h1><a href="/learn/">まなぶ</a></h1>
                    <p><a href="/learn/description.ja.html">OCamlとは?</a>、どんな<a href="/learn/success.html">ユーザー</a>がいて、<a href="learn/taste.html">どんな言語</a>なのか、<a href="/learn/tutorials/">チュートリアル</a>、<a href="/learn/">などなど…</a></p>
                </section>
                <section class="span4 home-feature">
                    <a href="/docs/">
                        <img src="/img/documentation-large.png" alt="ドキュメント">
                    </a>
                    <h1><a href="/docs/">ドキュメント</a></h1>
                    <p>OCamlの<a href="docs/install.html" >インストール</a>、
					<a href="https://opam.ocaml.org/pkg/">パッケージ情報</a>、
					<a href="http://caml.inria.fr/pub/docs/manual-ocaml/"
					target="_blank"
					>マニュアル</a>、<a href="/docs/cheat_sheets.html">チートシート</a>、<a href="/docs/">その他</a></p>
                </section>
            </div>
            <div class="row">
                <section class="span4 home-feature">
                    <a href="https://opam.ocaml.org">
                        <img src="/img/platform-large.png" alt="プラットフォーム">                    </a>
                    <h1><a href="https://opam.ocaml.org">パッケージ情報</a></h1>
                    <p><a href="https://opam.ocaml.org">OPAM OCaml パッケージマネージャ</a>を使って
					<a href="https://opam.ocaml.org/pkg/">何百ものパッケージ</a>をインストール</p>
                </section>
                <section class="span4 home-feature">
                    <a href="/community/">
                        <img src="/img/community-large.png" alt="コミュニティ">
                    </a>
                    <h1><a href="/community/">コミュニティ</a></h1>
                    <p>OCamlに関する<a href="/community/planet/">ニューストピック</a>、<a href="/community/mailing_lists.html">メーリングリスト</a>、<a href="/community/support.html">サポート</a>、<a href="/community/#ocaml-around-web">ネットでの情報</a></p>
                </section>
            </div>
            <div id="home-learn">
                <a href="http://try.ocamlpro.com">
                    <img class="hidden-phone" src="/img/learn-ocaml.png" alt="">
                    TryOCaml: 今すぐブラウザ上で OCaml を体験
                </a>
            </div>
        </div>
        <section id="home-news" class="span4 condensed">
            <h1 class="ruled">
                <a href="/community/planet/"
				title="See planet posts">ニュース</a>
                <a href="http://planet.ocaml.org/rss20.xml"
				title="Planet RSS feed"
				><img src="/img/rss.png" alt="RSS"></a>
            </h1>
			<ul class="news-feed" style="margin-bottom: 0px">
			<li><article>
			  <h1><a title="OCaml Users and Developers Workshop"
			       href="/meetings/ocaml/2014/">OCaml 2014</a></h1>
			  <p>September 5, 2014</p>
			  <a title="OCaml Users and Developers Workshop"
			     href="/meetings/ocaml/2014/">
			  <img alt="" src="/img/announcement.png" /></a>
			</article></li>
	        </ul>
            {{! cmd script/rss2html -n 5 --headlines http://planet.ocaml.org/rss20.xml !}}
            <p><a href="community/planet/">もっと見る…</a></p>
        </section>
    </div>
    <div class="row">
        <section class="span6 condensed">
            <h1><a href="learn/taste.html">OCamlの味わい</a></h1>
            ((! cat template/tryocaml.html !))
            ((! input template/front_code_snippet.html !))
            <p>この簡単な例にとどまらず、OCamlは<a href="/learn/taste.html">もっともっと強力</a>です！</p>
        </section>
        <section class="span6 condensed">
            <h1><a href='http://opam.ocaml.org/pkg/index-date.html'>パッケージ</a></h1>
            ((! input template/front_package.mpp !))
        </section>
    </div>
</div>
