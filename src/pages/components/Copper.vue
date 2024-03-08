<template>
    <h3 class="mt-10">Copper</h3>
    <v-table>
        <thead>
            <tr>
                <th class="text-left">
                    Name
                </th>
                <th class="text-left">
                    Code
                </th>
                <th class="text-left">
                    Sample
                </th>
            </tr>
        </thead>
        <tbody>
            <tr>
                <td>{{ copper50.name }}</td>
                <td>{{ copper50.hex }}</td>
                <td>
                    <v-sheet :color="copper50.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ copper100.name }}</td>
                <td>{{ copper100.hex }}</td>
                <td>
                    <v-sheet :color="copper100.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ copper200.name }}</td>
                <td>{{ copper200.hex }}</td>
                <td>
                    <v-sheet :color="copper200.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ copper300.name }}</td>
                <td>{{ copper300.hex }}</td>
                <td>
                    <v-sheet :color="copper300.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ copper400.name }}</td>
                <td>{{ copper400.hex }}</td>
                <td>
                    <v-sheet :color="copper400.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ copper500.name }}</td>
                <td>{{ copper500.hex }}</td>
                <td>
                    <v-sheet :color="copper500.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ copper600.name }}</td>
                <td>{{ copper600.hex }}</td>
                <td>
                    <v-sheet :color="copper600.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ copper700.name }}</td>
                <td>{{ copper700.hex }}</td>
                <td>
                    <v-sheet :color="copper700.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ copper800.name }}</td>
                <td>{{ copper800.hex }}</td>
                <td>
                    <v-sheet :color="copper800.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ copper900.name }}</td>
                <td>{{ copper900.hex }}</td>
                <td>
                    <v-sheet :color="copper900.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import {
    copper50,
    copper100,
    copper200,
    copper300,
    copper400,
    copper500,
    copper600,
    copper700,
    copper800,
    copper900,
} from 'rukkiecodes-colors';
</script>
