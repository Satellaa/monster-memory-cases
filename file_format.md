# File Format

Documents a Yu-Gi-Oh! monster memory case.
Must be a YAML file.

## Fields

- `temporaryBanished`: **string**
  
  The memory state when a monster returns from being temporarily banished.
  - must be one of: **Remembered**, **Forgotten**, **Refer to ruling**

- `flipFaceDown`: **string**
  
  The memory state when a monster is flipped face-down.
  - must be one of: **Remembered**, **Forgotten**, **Refer to ruling**

- `temporaryBanishedFAQs`: **FAQ[]** (optional)

  Frequently asked questions about temporary banishment memory cases.
  If provided, at least one official source from Konami or related official parties must be included.

  <details>
    <summary>FAQ spec</summary>

  ### FAQ

  - `question`: **string**
    
    The question being answered.
    - can use markdown formatting

  - `answer`: **string**
    
    The detailed answer to the question.
    - can use markdown formatting

  - `sources`: **Source[]**
    
    Sources supporting the answer.
    - must have at least one official source from Konami or related official parties

    #### Source
    - `text`: **string**
      
      The source title/description.
      - required when FAQs are present

    - `url`: **string**
      
      URL to the source document.
      - required when FAQs are present

  </details>

- `flipFaceDownFAQs`: **FAQ[]** (optional)
  
  Frequently asked questions about face-down memory cases.
  If provided, at least one official source from Konami or related official parties must be included.
  
  Uses the same FAQ specification as `temporaryBanishedFAQs`.