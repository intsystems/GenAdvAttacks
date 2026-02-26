# Title

<!-- Change `kisnikser/m1p-template` to `intsystems/your-repository`-->
[![License](https://badgen.net/github/license/kisnikser/m1p-template?color=green)](https://github.com/kisnikser/m1p-template/blob/main/LICENSE)
[![GitHub Contributors](https://img.shields.io/github/contributors/kisnikser/m1p-template)](https://github.com/kisnikser/m1p-template/graphs/contributors)
[![GitHub Issues](https://img.shields.io/github/issues-closed/kisnikser/m1p-template.svg?color=0088ff)](https://github.com/kisnikser/m1p-template/issues)
[![GitHub Pull Requests](https://img.shields.io/github/issues-pr-closed/kisnikser/m1p-template.svg?color=7f29d6)](https://github.com/kisnikser/m1p-template/pulls)

<table>
    <tr>
        <td align="left"> <b> Author </b> </td>
        <td> Name Surname </td>
    </tr>
    <tr>
        <td align="left"> <b> Consultant </b> </td>
        <td> Name Surname, PhD/DSc </td>
    </tr>
    <tr>
        <td align="left"> <b> Advisor </b> </td>
        <td> Name Surname, PhD/DSc </td>
    </tr>
</table>

## Assets

- [LinkReview](LINKREVIEW.md)
- [Code](code)
- [Paper](paper/main.pdf)
- [Slides](slides/main.pdf)

## Abstract

Глубокое обучение широко используется для решения задач в анализе временных рядов в таких областях, как медицина, финансы и т.д. Однако, одним из ключевых недостатков глубоких нейросетей остается уязвимость к адверсальным атакам. Такие атаки позволяют создавать малые возмущения входных данных, способные приводить к неверным предсказаниям моделей. Большинство известных методов атак опирается на доступ к градиентам целевой модели, однако в реальных условиях такая информация может быть недоступна. Если рассмотреть большие языковые модели, то они зачастую не дообучаются на отдельные задачи, т.е. у них нельзя получить градиент.

В своей работе мы предлагаем использовать атаки, основанные на моделях, в котором возмущения генерируются отдельной моделью. В процессе тренировки мы обучаем генеративную модель возвращать такие возмущение, которые сильнее всего увеличивают функцию потерь целевой модели. Мы приводим дизайн атаки и эмпирические результаты, полученные на разных выборках с последовательными данными и с разными архитектурами моделей.

## Citation

If you find our work helpful, please cite us.
```BibTeX
@article{citekey,
    title={Title},
    author={Name Surname, Name Surname (consultant), Name Surname (advisor)},
    year={2025}
}
```

## Licence

Our project is MIT licensed. See [LICENSE](LICENSE) for details.
