# Neural Decoding Workshop

A collection of materials for running a neural decoding workshop, developed through the EFRI-BRAID program from 2023-2025. This repository contains everything needed to organize and conduct a hack-a-thon workshop to introduce undergraduate students to neural decoding, machine learning applications, and brain-computer interfaces.

## Repository Structure

```
neural-decoding-workshop/
├── curriculum/          # Core teaching and dataset materials
├── admin/              # Workshop organization and logistics
├── templates/          # Forms and templates for registration and feedback
├── archive/            # Historical materials from previous workshops (2023-2025)
└── README.md          # This file
```

### [curriculum/](curriculum/)
Contains all teaching materials, datasets, and hands-on exercises. Includes:
- **Dataset materials**: Jupyter notebooks and documentation for multiple neural datasets
- **Introductory lectures**: Foundational content on neural decoding concepts and datasets
- **Mini-workshops**: Focused sessions on specific topics (ML, statistics, data visualization, etc.)

### [admin/](admin/)
Everything needed to plan and execute the workshop, including:
- **Judging**: Rubrics and scoring sheets for project evaluations
- **Outreach**: Flyers, promotional materials, and example contact lists
- **Planning**: Example schedules, task assignments, and team rosters

### [templates/](templates/)
Reusable forms and templates for:
- Participant registration and sign-up
- Feedback collection

### [archive/](archive/)
Historical materials from previous workshop iterations (2023, 2024, 2025) for reference 


### For Workshop Organizers

1. **Review the Structure**: Start with this README and the README files in each subfolder
2. **Check Admin Materials**: Review `admin/planning/` for schedules and task lists
3. **Prepare Curriculum**: Get to know materials in `curriculum/`
4. **Customize Templates**: Adapt forms in `templates/` for your needs
5. **Plan Timeline**: Use examples in `admin/planning/` to create your workshop schedule

### For Instructors

1. **Explore Datasets**: Review materials in `curriculum/dataset-materials/`
2. **Review Lectures**: Check `curriculum/intro-lectures/` for opening presentations
3. **Test Notebooks**: Run through Jupyter notebooks to ensure all dependencies work
4. **Customize Content**: Adapt mini-workshops to your audience's background

### For Participants

1. **Start with Introduction**: Begin with `curriculum/intro-lectures/neural-decoding-introduction.ipynb`
2. **Explore Datasets**: Pick a dataset from `curriculum/dataset-materials/` that interests you
3. **Learn Techniques**: Attend mini-workshops based on your goals and interests
4. **Build Projects**: Apply learned techniques to your chosen dataset

## Workshop Content

### Datasets Included
- **MC-Maze**: Motor cortex recordings during maze navigation tasks
- **Monkey Fingers**: Motor control and finger movement neural recordings
- **Willet Speech**: Speech brain-computer interface dataset
- **Zebra Finch**: Neural recordings from songbird vocal learning

### Topics Covered
- Introduction to neural decoding and BCI
- Data visualization and storytelling
- Statistical analysis of neural data
- Linear machine learning approaches (Naive Bayes, Logistic Regression, SVM)
- Nonlinear ML techniques
- Latent neural dynamics
- Tips and tricks for working with neural data
- Neural decoding model gallery

## Technical Requirements

### Software Dependencies
- Python 3.8+
- Jupyter Notebook or JupyterLab
- Common scientific Python libraries (NumPy, SciPy, Pandas, Matplotlib, Scikit-learn)
- Additional libraries as specified in individual notebooks

### Recommended Setup
```bash
# Create a virtual environment
python -m venv workshop-env
source workshop-env/bin/activate  # On Windows: workshop-env\Scripts\activate

# Install common dependencies
pip install numpy scipy pandas matplotlib scikit-learn jupyter
```

## Contributing

This repository represents years of refinement and community input. If you run a workshop using these materials:
- Share your adaptations and improvements
- Report issues or unclear instructions
- Contribute new datasets or exercises
- Provide feedback on what worked well

## License

See [LICENSE](LICENSE) file for details.

## Contact

For questions about running a workshop or using these materials, please refer to the contact information in the admin materials or reach out to the EFRI BRAID program coordinators.

## Acknowledgments

These materials were developed through the EFRI BRAID program with contributions from numerous instructors, organizers, and participants across multiple workshop iterations from 2023-2025.

---
