[Türkçe](#türkçe) · [English](#english)

<a id="türkçe"></a>

# S3 Browser Gizlilik Politikası

Sürüm: 1.1 · Yürürlük tarihi: 14.10.2026

Geliştirici: Sedat Üstünova (bireysel geliştirici) · İstanbul, Türkiye

İletişim: sedat@s3dat.com

## Yerel çalışma ve kapsam

Bu politika, S3 Browser’ın Mac’inizde sakladığı bilgileri, dış bağlantılarını ve sizin kontrollerinizi açıklar. Geliştirici, uygulama üzerinden kullanım analitiği veya telemetri toplamaz; yerel tarayıcı verilerinizi kendi sistemlerine göndermez, bu verilere erişmez ve bunları kendi sistemlerinde işlemez. S3 Browser Brain, tarayıcının kendi yerel hafızasıdır ve ayrı S3 Brain ürününün veri alanını kullanmaz. Ziyaret ettiğiniz siteler, Apple ve seçtiğiniz diğer hizmetler kendi koşullarına tabidir.

## Mac’inizde tutulan bilgiler

Normal gezinmede geçmiş, sayfa adresleri ve başlıkları, açık ve kapatılan sekmeler, pencere oturumları, yer imleri, çalışma alanları, site izinleri ve tercihler yerel profillerde saklanır. Brain’e kaydettiğiniz alıntılar, kaynaklar, notlar, arama indeksleri ve yerel yapay zekâ verileri de cihazınızda kalır. Etkinleştirdiğiniz davranış öğrenimi yerel gezinme örüntülerini işler. Tanılama kayıtları yereldir; destek için gönderme kararı size aittir. Yedekler ve dışa aktarımlar seçtiğiniz konumlarda bulunabilir; bazı yedekler hassas içerik içerebilir. Mac hesabınıza, yedeklerinize veya dosyalarınıza erişebilen kişiler bu verilere ulaşabilir.

Varsayılan olarak açık olan izleme takibi, desteklenen videolarda son kaydedilen oynatma konumunu, başlığı ve bölüm bilgisini saklar; Ana Sayfa’da izlemeye devam etmenizi sağlar. Sayfaların belirttiği kapak ve diğer medya görselleri ilgili sunuculardan indirilerek Mac’inizde önbelleğe alınır. Site simgeleri geçici bellekte tutulur. WebKit ayrıca çerez, site depolaması ve önbellek gibi web sitesi verilerini yönetir. Saklanan bilgilerin kapsamı kullandığınız özelliklere ve sitelere bağlıdır; geliştiricinin erişebildiği merkezi bir gezinme hesabı yoktur.

## Mac’inizden çıkan bilgiler

Adres alanına yazdığınız URL olmayan metin, önerileri almak için seçtiğiniz arama motoruna gönderilir. Arama motoru önerilerini Ayarlar’dan kapatabilirsiniz; özel pencerelerde bu metin hiçbir zaman öneri almak için gönderilmez.

Ziyaret ettiğiniz siteler ve sayfaların yüklediği hizmetler, standart web isteklerini, IP adresinizi, istek zamanını, tarayıcı bilgilerini, çerezleri ve gönderdiğiniz form verilerini alabilir. Adres alanındaki aramalar seçtiğiniz DuckDuckGo, Google veya Bing sağlayıcısına gider; varsayılan DuckDuckGo’dur. Site simgeleri ve sayfa görselleri sitelerin belirttiği adreslerden alınır; bu adresler ayrı görsel veya CDN sunucuları olabilir. Görsel istekleri de bağlantı bilgisi içerir. İsteğe bağlı sayfa takibi ve ön hazırlık etkinleştirildiğinde ilgili sitelere ek istekler yapılabilir.

Otomatik güncelleme kontrolü açıkken otomatik kontrol girişimleri arasında en az 24 saat bulunur. Güncelleme kaynağı GitHub’dır; bağlantılar GitHub’ın dosya sunucularına yönlendirilebilir. Sistem profili veya kullanım bilgisi gönderilmez; standart istek metaverileri, örneğin IP adresi ve istek zamanı, hizmete ulaşır. Elle başlattığınız kontroller de bağlantı kurar. Güncelleme kurulumu ayrıca onayınızı gerektirir.

Yerel S3 Browser Engine ve metin gömme modeli cihazda çalışır. Eksik model dosyalarını uygulama içinden indirdiğinizde Hugging Face ve dosya dağıtım altyapısı standart indirme isteklerini alır; bu indirme tarayıcı geçmişinizi veya Brain içeriğinizi göndermez. İsteğe bağlı çevrimiçi araştırma yalnız etkinleştirilip sizin tarafınızdan başlatıldığında kendi anahtarlarınızla çalışır. Brave Search araştırma sorusunu; OpenAI soru ve seçili kaynak alıntılarını alır. Araştırma kaynaklarına içerik alma istekleri yapılır. Sağlayıcıların ücretleri, saklama ve veri kullanımı kendi koşullarına tabidir.

**Claude, Codex ve S3 Agent Bridge.** “Claude’a Sor” veya “Codex’e Sor” özelliğini kullandığınızda yazdığınız mesaj ile eklediğiniz ekran görüntüsü, seçili metin, görsel veya bağlantı; Mac’inizde kurulu Claude Code veya Codex aracılığıyla, kendi hesabınızla Anthropic’e veya OpenAI’a gönderilir. Bu sağlayıcılar verileri kendi koşullarına göre işler ve kullanım ücretleri hesabınıza yansıyabilir. Sohbet geçmişi yalnız bu Mac’te saklanır; Ayarlar’dan silebilirsiniz. S3 Agent Bridge’i Claude Code veya Codex gibi bir ajana bağladığınızda o ajan, verdiğiniz izinler ölçüsünde normal pencerelerdeki sekmeleri okuyabilir, sayfalarda işlem yapabilir ve okuduğu içeriği kendi sağlayıcısına gönderebilir; yaptığı işlemler yerel denetim kaydında tutulur. Bu özellikler yalnız sizin bağlantı veya gönderim işleminizle çalışır. Gizli pencerelerde hiçbir şey gönderilmez ve ajanlar gizli pencereleri göremez.

## Parolalar, API anahtarları ve uzantılar

Web sitesi parolaları Apple Parolalar ve macOS sistem Otomatik Doldur üzerinden yönetilir. S3 Browser kendi parola kasasında web sitesi parolası, doğrulama kodu veya kart bilgisi saklamaz. Forma girdiğiniz bilgiler ilgili siteye iletilir. Hassas bilgileri kendi isteğinizle notlara, alıntılara veya yedeklere eklememeye dikkat edin. Araştırma API anahtarları, web sitesi parolalarından ayrı olarak, yalnız bu Mac’te uygulamanın özel Keychain alanında saklanır; ilgili API sağlayıcısına kimlik doğrulama için gönderilir. Kurduğunuz uzantılar, verdiğiniz izinler kapsamında verilere erişebilir ve dış bağlantılar kurabilir. İzinlerini ve kendi gizlilik politikalarını inceleyin.

## Gizli pencereler ve kontroller

Gizli gezinme kalıcı normal geçmiş, Brain, öğrenme veya izleme kaydı oluşturmaz; WebKit geçici site deposu kullanır. İzleme takibi ve çevrimiçi araştırma burada çalışmaz. Gizli gezinme sizi sitelerden, ağ işletmecinizden veya internet sağlayıcınızdan gizlemez. İndirdiğiniz dosyalar siz silene kadar diskte kalabilir. Yasal kabul uygulama genelindedir; gizli pencere bu gerekliliği değiştirmez.

Kurulum sihirbazından veya Ayarlar’dan izleme takibini ve S3 Browser Engine’i kapatabilirsiniz. Ayarlar’da güncelleme kontrolünü, davranış öğrenimini, ön hazırlığı ve araştırma iznini yönetebilir; geçmişi, izleme kayıtlarını, Brain içeriğini ve site verilerini ilgili kontrollerden silebilirsiniz. Profil silme işlemi o profilin verilerini ve ilgili araştırma anahtarlarını temizler. Başka konuma alınmış yedekler ayrıca silinmelidir.

## Verileri kaldırma

Önce saklamak istediğiniz verileri yedekleyin; gerekirse uygulamadaki profil ve site verisi silme kontrollerini kullanın. Ardından S3 Browser’ı tamamen kapatın. Finder › Git › Klasöre Git ile `~/Library/Application Support/S3 Browser` klasörünü Çöp Sepeti’ne taşıyın. Uygulamayı silmek bu klasörü kendiliğinden silmez. WebKit verileri ayrıca `~/Library/WebKit/com.sedatustunova.s3browser` (WebsiteData ve WebsiteDataStore alt klasörleri), önbellekler `~/Library/Caches/com.sedatustunova.s3browser`, HTTP depolaması `~/Library/HTTPStorages/com.sedatustunova.s3browser`, tercihler `~/Library/Preferences/com.sedatustunova.s3browser.plist` altında bulunabilir. Yalnız bu uygulamaya ait bu konumları kaldırın; macOS sürümü yerleşimi değiştirebilir. İndirmeler, dışa aktarımlar, dış yedekler ve Apple Parolalar ayrıca yönetilir. Klasör silme Keychain anahtarlarını silmez; araştırma anahtarlarını uygulamada profil silerek veya Keychain Access’te `com.sedatustunova.s3browser.research.v1` hizmetine ait kayıtları kaldırarak temizleyin. Çöp Sepeti’ndeki ilgili verileri de silin; işlem geri alınamayabilir.

## Destek, çocuklar ve değişiklikler

sedat@s3dat.com adresine gönüllü gönderdiğiniz e-posta adresi, mesaj ve ekler yalnız talebinizi yanıtlamak için kullanılır; e-posta hizmeti de iletişimi işler. Gereksiz hassas bilgi göndermeyin. Destek verilerinin silinmesini bu adresten isteyebilirsiniz; talebi ve uygulanabilir saklama yükümlülüklerini değerlendirerek yanıtlarız. Herkese açık GitHub Issues bildirimleri herkesçe görülebilir; sır paylaşmayın.

Uygulama çocuklara özel olarak tasarlanmamıştır; gerekli hukuki ehliyet veya temsilci onayı kullanım koşullarında açıklanır. Çocukların destek yoluyla gereksiz kişisel bilgi göndermemesini sağlayın. Bu politika değişirse sürüm ve tarih güncellenir; uygulamada veya yayın reposunda duyurulur. Sorularınız ve talepleriniz için yukarıdaki adresi kullanın. Türkçe metin esas alınır.

---

<a id="english"></a>

# S3 Browser Privacy Policy

Version: 1.1 · Effective date: 14.10.2026

Developer: Sedat Üstünova (individual developer) · İstanbul, Türkiye

Contact: sedat@s3dat.com

## Local operation and scope

This policy explains local storage, external connections and your controls. The developer collects no usage analytics or telemetry, neither accesses local browser data nor sends or processes it on the developer’s systems. S3 Browser Brain stores local memory separately from the S3 Brain product. Websites, Apple and other services you choose have their own terms.

## Information stored on your Mac

Browsing stores history, page addresses and titles, open and closed tabs, window sessions, bookmarks, workspaces, site permissions and preferences in local profiles. Quotes, sources, notes, search indexes and local AI data saved to Brain also remain on your device. Enabled behavior learning processes local browsing patterns. Diagnostic records are local; sending them for support is your decision. Backups and exports may be in locations you choose and may contain sensitive material. People accessing your Mac account, backups or files may access this data.

Watch tracking is on by default. For supported videos it saves the last recorded playback position, title and episode information, allowing you to continue watching from Home. Cover and other media images specified by pages are downloaded from relevant servers and cached on your Mac. Site icons are held in temporary memory. WebKit manages cookies, site storage and caches. Storage depends on features and sites; no central browsing account is accessible to the developer.

## Information leaving your Mac

Non-URL text you type in the address field is sent to your selected search engine to fetch suggestions. You can turn off search engine suggestions in Settings; this text is never sent for suggestions in private windows.

Sites you visit and services loaded by pages may receive standard web requests, your IP address, request time, browser information, cookies and submitted form data. Address-field searches go to your chosen DuckDuckGo, Google or Bing provider; DuckDuckGo is the default. Site icons and page images come from addresses specified by sites, including separate image or CDN hosts. Image requests also contain connection information. Optional page monitoring and preparation may make additional requests to sites when enabled.

When automatic update checking is enabled, automatic check attempts are at least 24 hours apart. GitHub hosts the update source; connections may redirect to GitHub’s file servers. No system profile or usage information is sent; standard request metadata, such as IP address and request time, reaches the service. Manual checks also make connections. Installation requires separate approval.

S3 Browser Engine and the text embedding model run locally. Downloading missing model files in-app sends standard requests to Hugging Face and its file delivery infrastructure, without sending browsing history or Brain content. Optional online research runs with your own keys only when enabled and initiated by you. Brave Search receives the research question; OpenAI receives the question and selected source excerpts. Research sources receive content-fetch requests. Provider charges, retention and data use follow their own terms.

**Claude, Codex and S3 Agent Bridge.** When you use “Ask Claude” or “Ask Codex”, your message and any attached screenshot, selected text, image or link are sent through the Claude Code or Codex installed on your Mac, using your own account, to Anthropic or OpenAI. These providers process the data under their own terms, and usage may count against your plan. Conversation history is stored only on this Mac; you can delete it in Settings. When you connect S3 Agent Bridge to an agent such as Claude Code or Codex, that agent can, within the permissions you grant, read tabs in normal windows, act on pages and send what it reads to its own provider; its actions are kept in a local audit log. These features run only when you connect them or send something. Nothing is sent from private windows, and agents cannot see private windows.

## Passwords, API keys and extensions

Website passwords are managed through Apple Passwords and macOS system AutoFill. S3 Browser has no own password vault storing website passwords, verification codes or card details. Information entered into forms goes to the relevant site. Avoid voluntarily adding sensitive information to notes, quotes or backups. Research API keys, separate from website passwords, are stored only on this Mac in the app’s dedicated Keychain namespace and sent to the relevant API provider for authentication. Extensions you install may access data and make external connections under their permissions. Review permissions and privacy policies.

## Private windows and controls

Private browsing creates no persistent normal history, Brain, learning or watch records; WebKit uses temporary site storage. Watch tracking and research are disabled there. Private browsing does not hide you from sites, your network operator or internet provider. Downloads remain until deleted. Legal acceptance applies across the app; private windows do not change that requirement.

Turn off watch tracking and S3 Browser Engine in the setup wizard or Settings. Settings controls update checking, behavior learning, preparation and research permission. Delete history, watch records, Brain content and site data using their respective controls. Profile erasure clears that profile’s data and associated research keys. Backups elsewhere require separate deletion.

## Removing data

Back up important data; use profile and site-data deletion controls if needed. Fully quit S3 Browser. In Finder › Go › Go to Folder, move `~/Library/Application Support/S3 Browser` to the Trash. Uninstalling the app does not delete this folder. WebKit data may also reside in `~/Library/WebKit/com.sedatustunova.s3browser` (WebsiteData and WebsiteDataStore subfolders), caches in `~/Library/Caches/com.sedatustunova.s3browser`, HTTP storage in `~/Library/HTTPStorages/com.sedatustunova.s3browser`, and preferences in `~/Library/Preferences/com.sedatustunova.s3browser.plist`. Remove only these app-owned locations; macOS versions may change their layout. Manage downloads, exports, backups and Apple Passwords separately. Deleting folders does not remove Keychain keys; erase research keys through profile erasure in the app or remove items for the `com.sedatustunova.s3browser.research.v1` service in Keychain Access. Empty the relevant Trash contents; deletion may be irreversible.

## Support, children and changes

Email addresses, messages and attachments voluntarily sent to sedat@s3dat.com serve only to answer requests; the email service also processes communications. Send no unnecessary sensitive information. Request deletion of support data at this address; we will assess your request and applicable retention obligations and respond. Public GitHub Issues are visible to everyone; do not post secrets.

The app is not designed for children; the terms describe required legal capacity or representative approval. Ensure children do not send unnecessary personal information through support. Changes to this policy update its version and date and are announced in the app or release repository. Contact us at the address above. The Turkish version prevails.
