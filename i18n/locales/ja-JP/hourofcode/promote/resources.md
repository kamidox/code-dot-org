* * *

title: <%= hoc_s(:title_resources) %> layout: wide nav: promote_nav

* * *

<link rel="stylesheet" type="text/css" href="/css/promote-page.css" />
</link>

# Hour of Codeを多くの人に知ってもらうには

## Hour of Code を開催するには [ガイド](<%= resolve_url('/how-to') %>)を見て下さい。

<%= view :promote_handouts %> <%= view :promote_videos %>

<a id="posters"></a>

## あなたの学校にこのポスターを貼ってください。

<%= view :promote_posters %>

<a id="social"></a>

## ソーシャル メディアに投稿してください

[![画像](/images/fit-250/social-1.jpg)](/images/social-1.jpg)&nbsp;&nbsp;&nbsp;&nbsp; [![画像](/images/fit-250/social-2.jpg)](/images/social-2.jpg)&nbsp;&nbsp;&nbsp;&nbsp; [![画像](/images/fit-250/social-3.jpg)](/images/social-3.jpg)&nbsp;&nbsp;&nbsp;&nbsp;

<%= view :social_posters %>

<a id="logo"></a>

## 以下のロゴをHour of Codeを広めるために使ってください。

[![画像](<%= localized_image('/images/fit-200/hour-of-code-logo.png') %>)](%= localized_image('/images/hour-of-code-logo.png') %)

[高解像度のバージョンをダウンロード](http://images.code.org/share/hour-of-code-logo.zip)

**"Hour of Code" is trademarked. We don't want to prevent this usage, but we want to make sure it fits within a few limits:**

  1. いかなる「Hour of Code」への言及も、それがあなたの独自のブランド名だと示唆する形ではなく、Hour of Code を草の根運動として参照する形で使われるべきです。 Good example: "Participate in the Hour of Code™ at ACMECorp.com". Bad example: "Try Hour of Code by ACME Corp".
  2. Use a "TM" superscript in the most prominent places you mention "Hour of Code", both on your web site and in app descriptions.
  3. ページに（またはフッターに）、CSEdWeek と Code.org へのリンクを含めて次の言葉を含めてください:
    
    *“The 'Hour of Code™' is a nationwide initiative by Computer Science Education Week[csedweek.org] and Code.org[code.org] to introduce millions of students to one hour of computer science and computer programming.”*

  4. No use of "Hour of Code" in app names.

<a id="stickers"></a>

## ステッカーを印刷して生徒に配布

(ステッカーは直径 1 インチ、1 枚 あたり63個)  
[![画像](/images/fit-250/hour-of-code-stickers.png)](/images/hour-of-code-stickers.pdf)

<a id="sample-emails"></a>

## Hour of Code を宣伝するために以下のメールを送ってみてください

<a id="email"></a>

## 学校や社長、友達にイベントを開催するよう頼んでください:

Computers are everywhere, changing every industry on the planet. But only one in four schools teach computer science. 良いお知らせは、私たちはこれを変えようとしているということです。 If you've heard about the Hour of Code before, you might know it made history. More than 100 million students have tried an Hour of Code.

Hour of Codeの取り組みによって、コンピュータサイエンスはGoogleやMSN、Yahoo!、 ディズニーのホームページに掲載されました。 Over 100 partners have joined together to support this movement. Every Apple Store in the world has hosted an Hour of Code. President Obama wrote his first line of code as part of the campaign.

This year, let's make it even bigger. I’m asking you to join in for the Hour of Code 2016. Please get involved with an Hour of Code event during Computer Science Education Week, <%= campaign_date('full') %>.

Get the word out. Host an event. Ask a local school to sign up. Or try the Hour of Code yourself—everyone can benefit from learning the basics.

http://hourofcode.com/ から始めよう<%= @country %>

<a id="media-pitch"></a>

## メディアをあなたが主催するイベントに招待してください:

**タイトル:** 地域の学校が、コンピュータサイエンスを子供達に教えるべく動きだしています

Computers are everywhere, changing every industry on the planet, but only one in four schools teach computer science. Girls and minorities are severely underrepresented in computer science classes, and in the tech industry. 良いお知らせは、私たちはこれを変えようとしているということです。

Hour of Codeの取り組みによって、コンピュータサイエンスはGoogleやMSN、Yahoo!、 ディズニーのホームページに掲載されました。 Over 100 partners have joined together to support this movement. Every Apple Store in the world has hosted an Hour of Code. President Obama wrote his first line of code as part of the campaign.

That’s why every one of the [X number] students at [SCHOOL NAME] are joining in on the largest learning event in history: The Hour of Code, during Computer Science Education Week (<%= campaign_date('full') %>).

この度は、[日付] に行うHour of Codeのイベントに参加して頂きたく、ご連絡を差し上げています。

The Hour of Code, organized by the nonprofit Code.org and over 100 others, is a global movement that believes the students of today are ready to learn critical skills for 21st century success. ぜひご参加ください。

**お問い合わせ:** [名前]、[肩書]、携帯: (212) 555-5555

**とき:** [イベントの日時]

**ところ:** [住所と道順]

ご連絡をお待ちしております。

<a id="parents"></a>

## 保護者に学校でのイベントについてお知らせしてください:

保護者各位

私たちは技術に囲まれた世界に住んでいます。 And we know that whatever field our students choose to go into as adults, their ability to succeed will increasingly depend on understanding how technology works.

But only a tiny fraction of us are learning **how** technology works. Only 1 in every four schools teach computer science.

That’s why our entire school is joining in on the largest learning event in history: The Hour of Code, during Computer Science Education Week (<%= campaign_date('full') %>). More than 100 million students worldwide have already tried an Hour of Code.

Our Hour of Code is making a statement that [SCHOOL NAME] is ready to teach these foundational 21st century skills. To continue bringing programming activities to your students, we want to make our Hour of Code event huge. I encourage you to volunteer, reach out to local media, share the news on social media channels and consider hosting additional Hour of Code events in the community.

This is a chance to change the future of education in [TOWN/CITY NAME].

See http://hourofcode.com/<%= @country %> for details, and help spread the word.

Sincerely,

Your principal

<a id="politicians"></a>

## あなたの学校のイベントに地元の政治家を招待してください:

Dear [Mayor/Governor/Representative/Senator LAST NAME]:

Did you know that computing is the #1 source of wages in the U.S.? There are more than 500,000 computing jobs open nationwide, but last year only 42,969 computer science students graduated into the workforce.

Computer science is foundational for *every* industry today. Yet 75% of schools don’t teach it. At [SCHOOL NAME], we are trying to change that.

That’s why our entire school is joining in on the largest learning event in history: The Hour of Code, during Computer Science Education Week (<%= campaign_date('full') %>). More than 100 million students worldwide have already tried an Hour of Code.

I'm writing to invite you to take part in our Hour of Code event and speak at our kickoff assembly. It’ll take place on [DATE, TIME, PLACE], and will make a strong statement that [State or City name] is ready to teach our students critical 21st century skills. We want to ensure that our students are on the forefront of creating technology of the future—not just consuming it.

Please contact me at [PHONE NUMBER OR EMAIL ADDRESS]. I look forward to your response.

Sincerely, [NAME], [TITLE]