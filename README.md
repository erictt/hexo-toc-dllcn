# hexo-toc-dllcn
hexo-toc的修改版，防止和next的侧边栏导航冲突，删除了部分配置
## Install

```node
npm install hexo-toc-dllcn --save
```

## Options

```yaml
mdtoc:
  maxdepth: 3
  class: toc
  decodeEntities: false
  anchor:
    symbol: '#'
    style: header-anchor
```

- `maxdepth`: Use headings whose depth is at most maxdepth.
- `class`: The CSS Class for the toc. (*Default is `false`*)
- `decodeEntities`: Select whether to enable decode entities. ( *Default is `false`* and please see [#15](https://github.com/bubkoo/hexo-toc/pull/15)).
- `anchor`: Whether should have an anchor for each headings. (*Default is `false`*)
    - `symbol`: Which symbol you want the anchor be. (*Default is `#`*);
    - `style`: The CSS class for the anchor, (*Default is `header-anchor`*);
