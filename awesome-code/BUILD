python_requirements('requirements.txt')

python_library(
  name = 'awesome-lib',
  dependencies = [
    ':scikit-learn',
  ]
)

python_binary(
  name = 'awesome-app',
  source = 'hello.py',
  dependencies= [
	':awesome-lib', #Hiding scikit-learn in a lib dependency since this seems to get pants to resolve numpy & scipy before scikit-learn
	':numpy',
        ':scipy'
    ],
)

