metadata-json-linter
--------------------

Simple tool to validate and lint metadata.json files in Puppet modules.



install
-------

```shell
gem install metadata-json-lint
```



usage
-----

```shell
metadata-json-lint /path/too/metadata.json
```



rake
----


```ruby
task :metadata do
  sh "metadata-json-lint metadata.json"
end
```




