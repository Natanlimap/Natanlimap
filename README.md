# Hello! 👋

I'm Natan de Lima, a Senior Software Engineer specializing in Flutter.

Here's a Flutter widget that represents me:

```dart
class Developer extends StatelessWidget with TechnicalSkills, SoftSkills {
  Developer({Key? key})
      : super(
            key: key,
            name: 'Natan de Lima',
            experienceYears: 4,
            tool: 'Flutter',
            isPassionate: true,
            isSolutionOriented: true,
            isProactive: true);

  final String name;
  final int experienceYears;
  final String tool;
  final bool isPassionate;
  final bool isSolutionOriented;
  final bool isProactive;

  @override
  Widget build(BuildContext context) {
    return MaterialApp(
      home: Scaffold(
        body: Center(
          child: Text('Transforming complexities into elegant solutions. 
                       Built with $tool. 
                       Total years of experience: $experienceYears'),
        ),
      ),
    );
  }

  @override
  List<TechnicalSkills> get technicalSkills => [
        FlutterDartExpert(),
        ScalableArchitectureCreator(),
        CI_CDImplementer(),
        BugsSolver(),
      ];

  @override
  List<SoftSkills> get softSkills => [
        TeamWorker(),
        QuickLearner(),
        EffectiveDecisionMaker(),
        PressureHandler(),
        DeadlineMeet(),
      ];
}
```

This widget exemplifies my passion for transforming complexities into elegant, effective solutions using Flutter, which has been my primary tool for over four years.

## Hard Skills
- Expert in Flutter and Dart
- Development of scalable software architectures
- Implementation of Continuous Integration / Continuous Delivery (CI/CD)
- Efficient bug solving and performance optimization

## Soft Skills
- Excellent teamwork and communication skills
- Proactive and capable of making effective decisions
- Ability to quickly learn and adapt to new technologies
- Skill in handling pressure and meeting deadlines
