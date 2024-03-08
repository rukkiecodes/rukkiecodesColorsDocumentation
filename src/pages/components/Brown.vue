<template>
    <h3 class="mt-10">Brown</h3>
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
                <td>{{ brown50.name }}</td>
                <td>{{ brown50.hex }}</td>
                <td>
                    <v-sheet :color="brown50.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ brown100.name }}</td>
                <td>{{ brown100.hex }}</td>
                <td>
                    <v-sheet :color="brown100.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ brown200.name }}</td>
                <td>{{ brown200.hex }}</td>
                <td>
                    <v-sheet :color="brown200.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ brown300.name }}</td>
                <td>{{ brown300.hex }}</td>
                <td>
                    <v-sheet :color="brown300.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ brown400.name }}</td>
                <td>{{ brown400.hex }}</td>
                <td>
                    <v-sheet :color="brown400.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ brown500.name }}</td>
                <td>{{ brown500.hex }}</td>
                <td>
                    <v-sheet :color="brown500.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ brown600.name }}</td>
                <td>{{ brown600.hex }}</td>
                <td>
                    <v-sheet :color="brown600.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ brown700.name }}</td>
                <td>{{ brown700.hex }}</td>
                <td>
                    <v-sheet :color="brown700.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ brown800.name }}</td>
                <td>{{ brown800.hex }}</td>
                <td>
                    <v-sheet :color="brown800.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
            <tr>
                <td>{{ brown900.name }}</td>
                <td>{{ brown900.hex }}</td>
                <td>
                    <v-sheet :color="brown900.hex" width="70" height="30" elevation="5" rounded="lg"></v-sheet>
                </td>
            </tr>
        </tbody>
    </v-table>
</template>



<script setup>
import {
    brown50,
    brown100,
    brown200,
    brown300,
    brown400,
    brown500,
    brown600,
    brown700,
    brown800,
    brown900,
} from 'rukkiecodes-colors';
</script>
