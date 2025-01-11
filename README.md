
      if (workspace && Object.keys(workspace).length === 0) {
        workspace.folders.push({
          name: 'projects',
          path: env.PROJECTS_ROOT,
        });
        saveRequired = true;
      }
