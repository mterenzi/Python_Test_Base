# Test Base
A starter project to set up and use automated testing in Python, locally and with GitHub Actions.

Configuration Steps:
    
    1. Rename package directory
    
    2. Open setup.cfg...
        Change fields:
            name
            description
            author
            licence
            packages
            install_requirements
            python_requries
            [options.package.data]
            
    3. Install package to env in edit mode:
        pip install -e .
        
    4. Change test code.
    5. Change source code.

 
Test Icon Badge:

![Tests](https://github.com/mCodingLLC/SlapThatLikeButton-TestingStarterProject/actions/workflows/tests.yml/badge.svg)
