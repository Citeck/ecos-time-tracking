![Citeck ECOS Logo](https://raw.githubusercontent.com/Citeck/ecos-ui/develop/public/img/logo/ecos-logo.svg)

**Read this in other languages: [Русский](README.RU.MD)**

# Time tracking

The `Time tracking` module provides a solution for setting work logs. Module is realized as an aspect to the data type.

## Cross-workspace journal

The `ecos-time-tracking-all-journal` journal lists time entries across accessible workspaces. The Time spent column shows a total below the table for all matching entries, including entries on other pages. The total respects the journal filters and workspace scope. Durations in rows and in the total are displayed in hours, minutes and seconds, without converting hours to days (for example, 25h instead of 1d 1h).

By default, Start date is filtered from one month ago through the current time. This is a relative interval that advances with time. Users can change or remove the filter; saved journal settings retain their own filters. The ordinary time tracking journal is unchanged.

## Get started

If you are new to Citeck platform and would like to load the software locally, we recommend you download the Dockerized version from [Demo repository](https://github.com/Citeck/citeck-community).

## Useful Links

- [Documentation](https://citeck-ecos.readthedocs.io/ru/latest/index.html) provides more in-depth information.

## Contributing

We welcome contributions from the community to make Citeck even better. Everyone interacting in the Citeck project’s codebases, issue trackers, chat rooms, and forum is expected to follow the [contributor code of conduct](https://github.com/rubygems/rubygems/blob/master/CODE_OF_CONDUCT.md).

## Support

If you need any assistance or have any questions regarding Citeck `Time tracking`, please create an issue in this repository or reach out to our [support team](mailto:support@citeck.ru).

## License

Citeck `Time tracking` is released under the [GNU Lesser General Public License](LICENSE).
