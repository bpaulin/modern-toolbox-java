custom_build(
  'modern-toolbox-java',
  'mvn -f app/pom.xml compile jib:dockerBuild -Dimage=$EXPECTED_REF',
  deps=['app/src'])

k8s_yaml('deploy/k8s.yaml')
