# Release Notes

{%- macro release_header(release='v0.0.0',release_date='(01/01/1970)',name_space='mattbuske/mkdocs-template') %}
## <a href="https://github.com/{{ name_space }}/releases/tag/{{ release }}" target="_blank" title="{{ release }} Release" alt="{{ release }} Release">**{{ release }} {{ release_date }}**</a>
{% endmacro -%}

{{ release_header('v0.1.0','(03/29/2023)') }}
- Created repo, initial commit
