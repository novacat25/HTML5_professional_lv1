# Description

A HTML Element about representing annotations: the pronunciation of Japanese, or Chinese chracters.

<ruby> 明日 <rp>(</rp><rt>Ashita</rt><rp>)</rp> </ruby>

<ruby>
  漢 <rp>(</rp><rt>Kan</rt><rp>)</rp> 字 <rp>(</rp><rt>ji</rt><rp>)</rp>
</ruby>

## Usage

- `<ruby></ruby>`: The target text
- `<rp>(</rp>` + `<rp>)</rp>`: ruby parenthesis → '(' or ')'
- `<rt>text</rt>`: annotations of the ruby text

```
<ruby> 明日 <rp>(</rp><rt>Ashita</rt><rp>)</rp> </ruby>
```

```
<ruby>
  漢 <rp>(</rp><rt>Kan</rt><rp>)</rp> 字 <rp>(</rp><rt>ji</rt><rp>)</rp>
</ruby>
```
