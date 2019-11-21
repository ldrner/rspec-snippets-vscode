# RSpec Snippets for Visual Studio Code

This extension for Visual Studio Code adds [RSpec](http://rspec.info/) snippets for Ruby.

## Features
- Contain snippets for the most common cases
- Snippets contain RSpec tips
- To be continued...

## Usage

### Base Snippets

| Snippet              | Purpose                                             |
| -------------------- | ----------------------------------------------------|
| `rspec`              | RSpec spec skeleton                                 |
| `des`                | describe                                            |
| `con`                | context                                             |
| `let`                | let                                                 |
| `letb`               | let!                                                |
| `it`                 | it                                                  |
| `pending`            | pending                                             |
| `sharex`             | shared_examples declaration                         |
| `itbl`               | it_behaves_like                                     |
| `expdo`              | expect multiline                                    |
| `exp`                | expect                                              |
| `expto`              | expect with block                                   |
| `itie`               | is_expected                                         |
| `subject`            | subject                                             |
| `subjectcls`         | subject(:subject) { described_class.new }           |
| `allrec`             | method stub                                         |

### Matcher Snippets

| Snippet              | Purpose                                             |
| -------------------- | --------------------------------------------------- |
| `expbe`              | expect(obj).to be                                   |
| `expbpm`             | expect(obj).to be_(truthy,falsey,nil)               |
| `expeq`              | expect(obj).to eq(other)                            |
| `expeql`             | expect(obj).to eql(other)                           |
| `expequal`           | expect(obj).to equal(other)                         |
| `expall`             | expect(arr).to all( matcher )                       |
| `expinclude`         | expect(obj).to include(el)                          |
| `expmatch`           | expect(obj).to match(patt)                          |
| `expcte`             | expect(obj).to contain_exactly(els)                 |
| `expexist`           | expect(obj).to exist                                |
| `expenw`             | expect(obj).to end_with(el)                         |
| `expstw`             | expect(obj).to start_with(el)                       |
| `exphat`             | expect(obj).to have_attributes(hash)                |
| `expsat`             | expect(10).to satisfy { expression }                |
| `expbko`             | expect(obj).to be_a_kind_of(type)                   |
| `expbio`             | expect(obj).to be_an_instance_of(type)              |
| `exprt`              | expect(obj).to respond_to(:foo)                     |
| `exprecw`            | expect(obj).to receive(msg).with(args)              |
| `expraise`           | expect { raise StandardError }.to raise_error       |

### Hooks Snippets

| Snippet              | Purpose                                             |
| -------------------- | --------------------------------------------------- |
| `befa`               | before(:all, :each, :suite, :context, :example)     |
| `aft`                | after(:all, :each, :suite, :context, :example)      |
| `aro`                | around(:example)                                    |

## Credits

Thanks to contributors of the https://github.com/SublimeText/RSpec repo for some RSpec snippets:
- [Tim Zeitz](https://github.com/tim3z)
- [Dimitar Dimitrov](https://github.com/mitio)
