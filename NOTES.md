# ТЭМДЭГЛЭЛ — Selah-ийн монгол орчуулга (монгол хэл)

Энэ файл **хүний гар эсвэл шийдвэр хүрсэн ишлэлүүдийг хадгална** — ишлэл бүрийг судалж буй
уншигч тэр ишлэлийг машин бичсэн үү, хүний гараар бичсэн үү, эсвэл шийдвэрийн дагуу
бичсэн үү, яагаад гэдгийг харахын тулд. Мөн тус тусын үгийн тухай шийдвэр, хүнд ишлэл,
одоо нээлттэй байгаа бөгөөд монгол хүний чихийг хүлээж буй асуултуудыг хадгална.

Бичлэг бүр: ишлэл · юу хийсэн · яагаад · огноо. Бичлэг бүрд еврей үг зогсоно. Бичлэгүүд
нь еврей хэлний морфологийг иш татдаг тул **англи хэлээр** бичигдсэн — орчуулгын
дүрмийн ажлын хэл нь англи. Бичлэгийг засна, чимээгүй устгахгүй — репозиторийн түүх бол
гэрчлэлийн нэг хэсэг.

Бичвэр хэрхэн бүтсэнийг `PROVENANCE.md`-ээс, засахаасаа өмнө `CONTRIBUTING.md`-г уншина уу.

---

## 1 · Hand-rendered verses

None yet. Every verse in this repository was rendered by the machine under the written
rules. After the pre-publication check (2026-10-06) some verses were taken out to be
rendered again — rows whose count did not match the Hebrew words, empty rows, and
English inside `⟨…⟩`. Those verses are being re-rendered now; any verse written by hand
will be recorded here as it is written.

## 2 · Decisions — word by word

Words that looked like faults and were kept as lawful Mongolian:

- **`эзэн` · `эзэн минь` in lower case** · for `אדני` / `אדון` addressed to a man
  (Genesis 44:19, *Миний эзэн өөрийн боолуудаас ⟨את⟩ асуусан нь…*) · kept — the word is
  lawful; only `Эзэн` / `ЭЗЭН` in the Name's seat is forbidden. · 2026-10-04
- **`бурхад` in lower case** · Psalm 97:7, `כל אלהים` → *бүх бурхад* · kept — the gods of
  the nations, as the rules allow; `Элохим` stands in the Name's seat. · 2026-10-04
- **`Билеам … хэлж байна`** · Numbers 24:3, `נאם בלעם` · kept — `נאם` before a man's name is
  the man's speech, not the prophetic formula `נאם יהוה` (*Яхвэ айлдаж байна*). Likewise
  2 Samuel 23:1, `נאם דוד` → *Давид … хэлж байна*. · 2026-10-04
- **`ו` → the converb `-ж / -ч`, or `ба` / `болон`** · Genesis 1:13 *Үдэш болж, өглөө
  болов* · the Russian conjunction *и* is forbidden; the converb is the Mongolian join.
  · 2026-10-04
- **Genesis 1:26, the plural** · `נעשה אדם בצלמנו כדמותנו` → *Хүнийг өөрсдийн дүр төрхөөр,
  өөрсдийн дүрслэлээр бүтээе* · kept plural, as the Hebrew has it. · 2026-10-04

## 3 · Hard verses and lens choices

- **Isaiah 10:6** · `חנף` → **`Бурхангүй`** (*godless*) · an ordinary adjective, not
  `Бурхан` standing in Elohim's seat. Recorded for a Mongolian ear: is it the right word
  for `חנף`, and should it stand in lower case? · 2026-10-06
- **Isaiah 53:5** · `מחלל` → **`нүцлэгдсэн`** · the Hebrew `חלל` reads *pierced / wounded*
  (Polal participle). A Mongolian ear is asked whether `нүцлэгдсэн` carries it. Recorded,
  not changed. · 2026-10-06
- **Psalm 23:1** · `מזמור` → **`зэмэр`** · recorded for a Mongolian ear: is this a Mongolian
  word, or a sound-copy of the Hebrew? · 2026-10-06

## 4 · Rulings made during the work

- **The Name `יהוה` → `Яхвэ`** · from the first verse. One spelling, four letters,
  Я-х-в-э. In the early checks a doubled-vowel spelling **`Яахвэ`** (and once `ЯХВЭ`,
  Leviticus 23:22) appeared and grew; it was written into the rules **by name**, in the
  forbidden column. When naming it barely moved it, every `Яахвэ` / `ЯХВЭ` in flows and
  glosses was corrected to `Яхвэ` mechanically. · 2026-10-04
- **`ו` is never Russian `и`** · Genesis 1:13 first came as *И үдэш болов, и өглөө* — added
  to the rules as a word-table row (`ו` → `-ж / -ч`, `ба`). · 2026-10-04
- **Latin look-alike letters inside Cyrillic words** · *Маxанайм* (Latin x), *Рeуэл*
  (Latin e) — added to the letter list; corrected mechanically to their Cyrillic twins
  only where the whole word then reads Cyrillic. Half-romanized words the mapping cannot
  heal were rendered again. · 2026-10-04
- **Hebrew surfaces restored** · after the rendering, many Hebrew `surface` fields were
  found overwritten with Cyrillic (whole words such as *элохим*, single letters swapped).
  Every one was restored from the Hebrew text; the Hebrew in this repository is the
  Hebrew. · 2026-10-04

## 5 · What remained

At the end of the first rendering (2026-10-04) these were kept for review, not silently
dropped:

- **`⟨את⟩` in the flow does not match the word rows** (the re-rendered version kept):
  1 Kings 11:20, 16:19 · 1 Samuel 10:19, 31:12 · 2 Kings 10:16 · Deuteronomy 14:9 ·
  Exodus 2:22, 13:5, 26:33, 32:35, 34:32, 35:14, 35:15, 38:22 · Ezekiel 4:3 ·
  Genesis 9:20, 45:5, 45:13 · Isaiah 36:2, 63:3 · Jeremiah 31:33, 33:26 · Joshua 10:1 ·
  Judges 1:17 · Leviticus 4:33, 23:11, 25:18 · Nehemiah 6:18 · Numbers 13:17.
- **A stray letter** · 2 Chronicles 15:2 (Kazakh `һ` in *Йеһуда*) · Ezra 10:36 (Latin
  letters in *Мерemoth*).
- **Word-row count differs from the English rendering's rows** · a list of verses is kept; the
  pre-publication check (2026-10-06) is re-checking the rows against the Hebrew now.

## 6 · Open issues

- **`Бурхан` in Elohim's seat** · Leviticus 23:22 (*Би таны Бурхан Яхвэ мөн*), 23:28,
  23:40 · Deuteronomy 28:13, 28:15 (*Яхвэ болон чиний Бурхан* — the Name and Elohim split
  by *болон*) · Zechariah 6:15. `אלהיכם` / `אלהיך` should read `Элохим`. Render again.
- **Psalm 97:7** · the flow opens *Бурханчлуудыг биш* — a phrase the word row does not
  carry. Flow and row disagree; render again.
- **`Яахвэ` left inside `⟨את⟩` mark fields** · Numbers 32:31 · 2 Chronicles 7:22 ·
  2 Samuel 6:15 · 1 Kings 18:30. The mechanical correction reached flows and glosses, not
  the `marks` field of the `⟨את⟩` token. A mechanical fix.
- **Genesis 1:2** · `פני` (twice) → `рүүнгүй` · not *face / surface*; the flow carries
  *гүн рүүнгүй дээр*. Render again.
- **Psalm 65:12** · `שנת` → `жил'-г` · a stray apostrophe and hyphen. A mechanical fix.
- **2 Chronicles 15:2 · Ezra 10:36** · the stray letters above.
- **For a Mongolian ear** (from the rules): the Name's form — `Яхвэ` or `Яхве`? Personal
  names — Hebrew sound (`Аврахам`, `Йицхак`, `Яаков`) or the traditional forms? Is
  `эш үзүүлэгч` right for `נביא`? Are `Шаббат` and `Мишкан` spelled well?
