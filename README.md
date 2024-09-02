### Hi there 👋

```python
class Attributes(StarKeyJON):
	@staticmethod
	def contact() -> str:
	    name     = "J.O.N."
	    
	    return name
	
	@staticmethod
	def life() -> tuple:
		langs         = ['English', 'Spanish', 'French']
		nationalities = self.langs.remove('French', 'Spanish', 'English').append('USofA')
		age           = redacted
		
		return langs, nationalities, age
	
	@staticmethod
	def coding() -> tuple:
		langs = {
      			'expert': ['python', 'solidity', 'yul'],
			'advanced':   ['rust', 'typescript/javascript', 'wasm', 'c', 'c++'],
			'intermediate': ['go', 'swift', 'kotlin', 'move'],
			'learning': ['c#', 'java', 'cobol', 'r']
		}
		specialities  = ['ML/AI', 'web/app', 'web3', 'software design', 'fullstack']
		env = ['vscode', 'vim', 'text editor']
	        interests = ['cryptography', 'dApps', 'ML/AI', 'communications']
		
		return langs, specialities, env, interests

```

"If You Put Your Mind To It, You Can Accomplish Anything" - George McFly (Back to the Future)
