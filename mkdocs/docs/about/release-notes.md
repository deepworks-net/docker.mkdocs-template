# Release Notes

{%- macro release_header(release='v0.0.0',release_date='(01/01/1970)',name_space='mattbuske/mkdocs-template') %}
## <a href="https://github.com/{{ name_space }}/releases/tag/{{ release }}" target="_blank" title="{{ release }} Release" alt="{{ release }} Release">**{{ release }} {{ release_date }}**</a>
{% endmacro -%}

{{ release_header(release=‘v0.2.0’,release_date=’(04/03/2023)’) }}
- Changed root `docs` folder to `mkdocs`
- Updated files to account for Repo ownership change
- Fixed issue with broken release notes 

{{ release_header(release=‘v0.1.1’,release_date=’(03/29/2023)’) }}
- Added extra.js shell file for any custom javascript

{{ release_header(release='v0.1.0',release_date='(03/29/2023)') }}
- Created repo, initial commit
